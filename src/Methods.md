# Method Plan

The methods used to generate this report can be considered trustworthy based on:
- The data is coming from a peer reviewed research that is publicly available.
- the dataset is quite large, encompassing over 500 data points
- All the N/A values are removed from the dataset and the response variable is transformed using a log function to have a less skewed distribution.
    - to account for the data points where the area burned was 0, we uniformly added 1 to every data point so that the differences between the data points were retained

In relation to the research question, our null hypothesis states that we will not see a difference in the area burned between the two wind speed categories.

### Is it enough?

The preliminary results seen seem to suggest that there may not be a considerable difference in average area burned when wind is categorized as high or low. However, we cannot come to a definitive conclution without any evidence, so we need to test the likelyhood of our statistic under the null hypotheis first and foremost.

### Plan for Further Research

Our plan is to:
- Construct a 95% confidence interval from a bootstrap distribution of difference in means
- Conduct a hypothesis test for our statistic using a simulation based approach with a 5% significance level
- Conduct a hypothesis test for our statistic using a theory based approach with a 5% significance level
- Analyze the results to come to a conclution regarding our research question

### Expectations

At first glance, the preliminary results don't seem to suggest a strong relationship between area burned and wind speed. This could suggest that wind speed is not as important of a factor as the prior research lead us to believe, but it could also be a symptom of some flaw in our approach. It could very well be the case that our catagorization of the wind speed was too arbitrary and that we needed a more definitive metric to define "high" and "low".

### More Research Needed

It's understandable that wind speed is a relatively easy attribute to measure for wind, and is thus an attractive variable to depend upon for simplistic models. If our perlimary results prove valid, it may indicate the need revaluate the strength of the wind speed factor and develop more complex models that take in a wider range of parameters (presumably to the tune of more accurate results).