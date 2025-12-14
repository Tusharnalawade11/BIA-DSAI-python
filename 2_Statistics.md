# <u>Statistics</u>


## Descriptive statistics
- Method of organizing, summarize data in informative way (insights) 
- Data analytics

## Inferential statistics
- To infer about the data from the sample and gather inference of the population
- Eg. To understand the consensus of people about some govt scheme
- Done by Data Scientist 


## Types of data
1. Numerical - numbers
    1. Continuous
        - many options - color scheme, age, weight
    2. Discrete
        - limited options - shoe size, sample size

2. Categorical - words
    1. Ordinal
        - having hierarchy/has order - Ratings, education level
    2. Nominal
        - no hierarchy/order - breed of animal, gender


## Data harnessing
Collecting Data --- by experiment, survey
<hr>

## Measures of Central Tendency
1. Mean: use when data is in the suitable range
2. Median: use when data has outliers or extreme values 
3. Mode: Most occuring value, when there is text data

- Data scientist will do data cleaning, make inferences  and use MCT.
- Data analyst will just do data cleaning and gain insights.

## Measures of Dispersion
1. Variance
` v = sum(sq(x))`
2. Standard Deviation
` sd = sqrt(v)`


+ Missing value treatment
+ outliers treatment


3. IQR
  `Q2 = median[min: max]`,
  `Q1 = median[min: Q2]`,
  `Q3 = median[Q2 : max]`
    **`IQR = Q3-Q1`**
> 
    Outlier removal formula : 
    [Q1-1.5(IQR), Q1+1.5(IQR)]*
*Remove values outside this range

## Measure of Symmetricity

1. Skewness
    - Positive [Mode < Median < Mean]
    - Negative [Mode > Median > Mean]
    - Unskewed(Symmetric) [Mean = Mode = Median]

2. Kurtosis
    - Measure of peakedness of probability distribution
