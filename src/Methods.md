# Method Plan

The methods used to generate this report can be considered trustworthy based on:
- The data is coming from a peer reviewed research that is publicly available.
- the dataset is quite large, encompassing over 500 data points
- All the N/A values are removed from the dataset and the response variable is transformed using a log function to have a less skewed distribution.
    - to account for the data points where the area burned was 0, we uniformly added 1 to every data point so that the differences between the data points were retained

In relation to research question, our null hypothesis states that we will not see a difference in the area burned between the two wind speed categories.

## Is it enough?
The preliminary results seen seem to suggest that there may not be a considerable difference in average area burned when wind is categorized as high or low.

However, the plots we produced are not enough to come to a conclusion because we do not know how significant the differences in the area burned really is. To be able to come to a conclusion whether or not the wind speed has an effect on the area burned, we need to first see evidence that the data is statistically unlikely under the null hypothesis, therefore allowing us to reject it.

## Plan for Further Research

Our plan is to include:
- hypothesis test around the difference in means of area burned across the two wind categories
- a confidence interval around this difference in means
- a bootstrap distribution pulled from our sample data
    - which could be used to produce that confidence interval
- calculate the p-value to find it's likelyhood under the null hypothesis
- the t-value and compare it to the sample's t-distribution

## Expectations

From eyeballing the preliminary results, we don't expect to find a significant difference in averages of the area burned between the two categories. These results might suggest that the wind speed isn't as important to track for predicting the severity of wildfires (at least in Portugal). However, it might also point for a need for more comprehensive data, or a data set that spans over a longer period of time, or that our model needs to account for more properties about the wind's behaviour outside of the wind speed.

### Reflection

The results from this project could signify to bodies that care about wildfires that wind speed isn't enough to be able to predict the severity of future wild fires (the dependency on this single variable is dangerous), and that there needs to be more investment in finding a property that better fits their area.

### More Research Needed
Is it understandable that wind speed is a relatively easy attribute to measure for wind, thus an attractive variable to depend upon for simplistic models.

Our research could point for the need for new comprehensive methods of measuring other wind properties, which presumably would be better at predicting area burned. It could also raise to questions whether or not the wind speed is truly is the one of the most significant factors for accurate predictive models, or whether the forest environment has other behaviours that contribute significantly to the severity of these events.