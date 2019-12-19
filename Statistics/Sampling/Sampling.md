# Sampling Techniques
---

Sampling is issued when it is difficult to deal with the entire population data or when it is hard to collect data from an entire population. So a subset of the records are selected from the population that are decent enough to represent the whole population.

Sampling techniques can be categorized into two groups *viz.* Probabilistic Sampling and Non-Probabilistic Sampling. 

### Probablistic Sampling

In Probabilistic Sampling, every record has some probability of being selected. Compared to non-probablistic sampling, this is hard to deal with but it gives a good representation of the Population. There are four sampling techniques that come under probablistic sampling. 

* **Random Sampling**
	- Random sampling is the most easy way to sample data from the population. Every record in the population dataset has an equal chance of being selected. For example, if there are 1000 records in the dataset, each record can be numbered from 0 to 999. Three numbers can be randomly chosen from 0 to 9 and a three digit number can be formed with these to select the record. For example, if the chosen numbers are 0, 9 and 4. then the 094 record can be selected. The disadvantages of this type of sampling method include biased sampling. If there are minor categories in the data, then these will be less in number in the final sample. 

* **Systematic Sampling**
	- Systematic sampling is a little different from random sampling in a way that the records are selected in a more organized manner than random picking. For example, every 10th record in the dataset will be picked. For example, if the data set has 1000 records and we need to pick 100 records from the sample, then picking every 10th record will give us the required sample. This is easy technique compared to random sampling but there is a lof of bias involved if the ordering is not proper. For example, if the dataset is ordered in such a way that every odd numbered record is a female and every even numbered record is a male then picking every 10th record would result in a sample consisting of completely males.

* **Stratified Sampling**
	- In stratified sampling, the entire population is sub divided into groups where in each group, records that belong to it have some common characteristic. This is a good technique when there are some minority categories in the data. Also, the number of records that can be selected from each group can be based on the number of records in each group. For example, if the population consists of three groups, with 1000 elephants, 2000 horses, 4000 cheetahs then we can select 10 elephants, 20 horses, 40 cheetahs to represent the population. If random sampling was used here, then more cheetahs would be selected than elephants due to the high presence in the population.

* **Clustered Sampling**
	- In clustered sampling, instead of selecting each record, cluster is sampled. The population is divided into several clusters and a clusters are picked at random. If a cluster is picked, all records belonging to that cluster will be a part of the sample. This type of sampling is especially used when we are dealing with large amount of area. For example, in a wide geographic area, if the users in the sample need to be contacted via mail, selecting everyone at random would incur a huge delay. If the area is clustered into groups based on the location then selecting few areas is a better choice as every body can be contacted easily.

### Non Probabilistic Sampling

In NP Sampling, some records will definitely not be selected unlike probabilistic sampling. So this would result in a sample not representative of the population but is more easier. NP Sampling involves 4 kinds of techniques as described below.

* **Choice Sampling**
	- This is particularly used in online surveys where the survey is given to only people who volunteer to take it. People who don't volunteer don't get to take the survey and hence are no studied. This technique results in a huge bias because there may be a common characterstic in people who volunteered and there may be a different characteristic among people who didn't volunteer which will not be surveyed if such technique is used.

___