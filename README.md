# Final-Exam

![Abalone](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZ6CTnfJsX8nsN_W_ByOarfeGh1t_NFrbkPUtj41wgru_YYZgu)

## Abalone Data Set

#### Domain
This dataset is drawn from a biological study of the population of Abalone. 

It originates from a 1994 dataset. 

Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn and
	Wes B Ford (1994) "The Population Biology of Abalone (_Haliotis_
	species) in Tasmania. I. Blacklip Abalone (_H. rubra_) from the North
	Coast and Islands of Bass Strait", Sea Fisheries Division, Technical
	Report No. 48 (ISSN 1034-3288)

#### Problem Statement
For a single set of physical measurements, we can use supervised learning to develop a regression model to predict the age of an abalone.

We examine a number of factors that relate to the age of male and female abalone.
The dataset to be examined contains the sex, length(mm), diameter(mm), height(mm), whole weight(g), shucked weight(g), viscera weight(g), shell weight(g), and rings.


#### Dataset and Inputs
In particular, we wish to understand the primary features that are predictive of the age of the abalone as indicated by the target feature `rings` + 1.5, with regards to `sex`, dimensional attributes (`length`, `diameter`, and `height`) and weight attributes(`whole weight`, `shucked weight`, `viscera weight`, and `shell weight`.)


#### Solution Statement
A solution to this problem will be to apply a prinicipal component analysis and then use a linear regression model.

#### Benchmark Model
A good naive benchmark would be to use either the mean or the median of the `rings` attribute.

#### Evaluation Metrics
Given that this is a regression task, we can measure the success of our model using the Mean Absolute Error. 
