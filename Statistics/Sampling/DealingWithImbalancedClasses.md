# Dealing with imbalanced class distributions
___

Sometimes, when we are dealing with data which have categories that are present in abundance or meagre, there is a need to follow a different sampling strategy to make sure that the sample generated has a uniform category distribution. If a minory class is sampled multiple times with replacement then it is called over sampling. If a majority class is sampled very less number of times, then it is called under sampling.

### Dealing with Minory Classes

1. **SMOTE**

	- SMOTE is an algorithmic way of creating new samples of the minority class instead of over sampling with replacement. 
	- In SMOTE, new samples are created using the existing samples by taking the records in the direction of the existing samples. 
	- Lets say, we have records of m features in our dataset. We can use SMOTE to create synthetic records from this dataset in the following way. 
		- For a given record, take the closes k neighbors and then for every pair of neighbors, get the difference between them. 
		- Then multiply this difference with a random number between 0 and 1. Then add this to the both the records in the pair. 
		- This will generate a new record in the direction of the original records. 
	- The number of neighbors to be selected can be decided based on the amount of oversampling required. 
	- For example, if you are willing to consider 5 nearest neighbors for every record and the amount of over sampling desired is 200% then you can select 2 neighbors from the 5 nearest neighbors. These two neighbors will generate 2 synthetic records for the considered record.