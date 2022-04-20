# Statistics

There are 2 sets of tools for statistics:
1. Descriptive Statistics: It is used to identify important elements in a dataset and describe the dataset.
2. Inferential Statistics: It explain those relationships via other elements.

```python
            Statistics
     Descriptive     Inferential
Univariate                Hypothesis Testing 
Bivariate                 Model Fitting
Multivariate

```

Descriptive statistics help us summarize the data. 
- It is the first step in exploratory data analysis.
- It helps us understand the data.
- It help you detect outlier.
- Plan to prepare data.
- It also helps us in feature engineering.

```python
          Descriptive
Univariate  Bivariate  Multivariate


```

Univariate: It involves single variable.

Bivariate: It involves 2 variables, examples: correlation and covariance.

Multivariate: It includes multiple variables, examples: corrilation matrix and covariance matrix.

### Lets understand Univariate Statistics

It is divided into 3 parts:

1. Measures of Frequency
- How often a particular value occur in data.
- It includes frequency tables and histogram.
- A histogram is a visualization where we plot the values, bucketized if needed on the x-axis and on the y-axis we have count of record.

2. Central Tendency
- Measure of central tendency for a variable try to determine one value that best represents your data.
- Common measures include average or the mean of your data, the median value and the mode.

Other measures of central tendency
- Geomatric mean
- Harmonic mean

They are used with ratios or rates

### Mean

- It is the single best value to represent your data. It not actually be the data point itself.
- It considers every point available in your data.
- It can be computed on discrete data as well as continuous data.

Discrete data can be numeric value that take on values from a predetermine subset such as star ratings.

Continuous data can take on any value in a range.

#### Mean is extremly sensitive to the presence of outlier.


### Median

- It is less influenced by the outlier.
- The median is that value in your data such that 50% of the dataset is either side of it.
- For calculating mean you have to sort the data in ascending or decending order and then use the middle element.
- It the data points are even then average the middle 2.
- The median might be the better measure of central tendency than the mean because it is much more robust to the presence of outliers.
- Like mean, Median does not consider very data point available in the dataset.
- The median can be computed on ordinal data, data that is not numeric but can be sorted like rating like good bad ugly very ugly.


### Mode

- The value that occurs most frequently in the data, if you plot a histogram, the highest bar represents the mode.
- Examples - casting votes in an election
- It is used with catagorical data, variables that take on a fixed set of values from a predetermined range, examples of catagorical data includes, days of a week, month of the year, makes of cars.
- Mode dont need to be unique.
- Mode is not great for continuous data that can take on any value within the range.

- Contiuous data needs to be descretized before you can perform mode computation.

3. Dispersion

It tells you how your dataset is spread out.

- Range(max-min) of your variable. It is sensitive to outliers.
            - Range completely ignores the mean, thats why variance comes in.

- Inter Quartile range: Difference between the values at the 75th percentile of your data and the 25th percentile of your data.
- Standard deviation and variance

#### Variance 

- Not only tells us how the numbers jumps around but also understands where your numbers are clustered.
- It also considers the mean.
- Variance is the second most important number to summarize your datapoints.
- Variance of the data is simply the sum of the squares of the mean deviations divided by the number of data points you have in your data.

Bessels Correction - put n-1 in the denominator while computing variance


## Probability

- It defines the extends to which an event is likely to occur and it is measured by the ratio of the favorable cases to the whole number of cases.

Probability Distribution
- It tells you how likely a particular value is to occur in your data.
- On x-axis the values are out distribution is to take on.
- On y-axis the curve, the probability that a variable take on a particular value.

Properties in the real world can be represented by a normal distribution also called a Gaussian Distribution or bell curve.

- 68% data points lie within one standard deviation from the mean.

#### In probability theory the law od large number is a theorem that describe the result of performing the same a large number of time.

Large numbers converges to the probability.

This flows from the law of large numbers, the actual frequency of the events converges to the expected probability of the events.



### Skewness

Skewness is a measure of asymmetry around the mean.

- To understand skewness, plot a probability distribution of data.
- Skewness of a data is usually measured with respect to normal distribution.
- Normaly Distributed data has a skewness = 0, it implies symmetry around mean value.

Two types-
- Right skewed(Positive Skewness) - the distribution where outliers and greater than the mean, where there is a lower bound but not an upper bound
- Left skewed(Negative Skewness) - the distribution where outliers and less than the mean, where there is a an upper bound but not lower bound 


### Kurtosis

How offen an extreme value occurs on either side of the mean.

- Normal distributed data has kurtosis = 3
- Excess kurtosis = greater than 3
- It represents the tail risk of the events
- If any data that has high kurtosis that means exteme events are more likely to occur.






