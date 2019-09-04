# EE 376A: Rumor Spreading
Rumor Spreading with Consistent Actors

Author: Sarah Hensley

Abstract: 
We investigate a model for rumor-spreading in a social network with actors that consistently output the same rumor. Modifying a previously developed model suggested in [1], we introduce liars and truth-tellers as “consistent actors”. Even when a small portion of the network is composed of “consistent actors”, they have a noticeable effect on dominant opinions. However, these consistent actors have little effect on the entropy within the memory of other nodes. From this, we conclude that the presence of consistent actors allows rumors to still spread while subtly forcing the dominant opinion to conform to their choice of rumor.

![](control.gif)
![](one_each.gif)

Aside from the technical analysis, this project also created a way to visualize the rumor spreading model. The gifs control.gif (above) and one_each.gif (below) show the evolution of each node’s “dominant opinion” over time, with the color scale sliding from blue to lavender to purple to pink to hot pink to red, to indicate the Hamming distance from the “true” (blue) rumor. The models are both with 100 nodes for 200 time steps, with the control.gif showing the vanilla model and the one_each.gif showing the model with one liar node and one truth teller node.

[1] Wang, Chao & Zhi-Xuan, Tan & Ye, Ye & Wang, Lu & Cheong, Kang & Xie, Neng-gang. (2017). A rumor spreading model based on information entropy. Scientific Reports. 7. 10.1038/s41598-017-09171-8. https://www.nature.com/articles/s41598-017-09171-8
