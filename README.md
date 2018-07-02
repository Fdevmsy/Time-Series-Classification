# Time Series Classification

**Shiyu Mou**
**shiyumou@usc.edu**

In this problem, I classified the activities of humans based on time series obtained by a Wireless Sensor Network.
The dataset was downloaded from: [https://archive.ics.uci.edu/ml/datasets/ Activity+Recognition+system+based+on+Multisensor+data+fusion+\%28AReM\ %29](https://archive.ics.uci.edu/ml/datasets/Activity+Recognition+system+based+on+Multisensor+data+fusion+\%28AReM\ %29). The dataset contains 7 folders that represent seven types of activities. In each folder, there are multiple files each of which represents an instant of a human performing an activity. Each file containis 6 time series collected from activities of the same person. There are 88 instances in the dataset, each of which contains 6 time series and each time series has 480 consecutive values.
In this practice, various ways of feature engineering were tested, logistic regression and naive bayes were used and compared.