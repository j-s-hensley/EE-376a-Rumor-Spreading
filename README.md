# EE-376A
Rumor Spreading with Consistent Actors

Author: Sarah Hensley

Abstract: 
We investigate a model for rumor-spreading in a social network with actors that consistently output the same rumor. Modifying a previously developed model, we introduce liars and truth-tellers as “consistent actors”. Even when a small portion of the network is composed of “consistent actors”, they have a noticeable effect on dominant opinions. However, these consistent actors have little effect on the entropy within the memory of other nodes. From this, we conclude that the presence of consistent actors allows rumors to still spread while subtly forcing the dominant opinion to conform to their choice of rumor.

Aside from the technical analysis, this project also created a way to visualize the rumor spreading model. The gifs control.gif and one_each.gif show the evolution of each node’s “dominant opinion” over time, with the color scale sliding from blue to lavender to purple to pink to hot pink to red, to indicate the Hamming distance from the “true” (blue) rumor. The models are both with 100 nodes for 200 time steps, with the control.gif showing the vanilla model and the one_each.gif showing the model with one liar node and one truth teller node.

Outreach:

For the outreach portion, I designed a rumor-spreading game. The premise was as follows: I have just adopted a cool new pet, and everyone it talking about what pet it is! The problem is, not everyone knows the right answer. You’re asking your friends to try to figure out what my pet is. 

Each player received one of the scorecards at Outreach_Handout.pdf to keep track of the rumors they had heard, and filled it out as in the second image filled_out_card.jpg. For four players (which was the most common number of players I had), the game started with Round 1, in which I told two players the correct pet, and one player the wrong pet. During the next round, everyone who had heard a “rumor” told two other players the most common rumor they had heard on the previous round, and one player the “wrong” rumor. This repeated on the next round. After some number of rounds (usually limited to three by the attention span of the participants), the players tried to guess what the original pet was. 

In most cases, all of the players correctly guessed the original pet! In a fully connected graph where the lie was told at random, which this game tried to emulate, all players should eventually determine the correct pet. The takeaway of the game was to understand how noise affects system dynamics, especially in a rumor spreading model. Overall, I played the game with over a dozen kids, and hopefully taught them something about rumor spreading!
