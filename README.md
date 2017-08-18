https://htmlpreview.github.io/?https://github.com/ThomasRoscher/GoT_predicting_character_death_R/blob/master/sif2.html

# GoT_predicting_character_death
For this project I wanted to see if social network analysis combined with ML algorithms is a valid approach to predict if a GoT character dies - or at least to evaluate his dead probability. The starting point is a self-written function that scraps a social network from each of the five books. The network is based on the idea that characters interact if there name/nickname occurs within n words. I then used those networks to derive several centrality measures for each character. Those measures which indicate different aspects of importance/strength finally were used to train and tune a variety of machine learning models. Based on cross-validation I found that a Neural Network with standardized features yields the best results.


