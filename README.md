# Introduction

This repository uses data from the [UC Irvine Machine Learning Repository](http://archive.ics.uci.edu/ml/), a popular repository for machine learning datasets. 
In particular, we will be using the "Hungarian Chickenpox Cases Data Set" which is available [here](http://archive.ics.uci.edu/ml/machine-learning-databases/00580/):

<p align="center">
  <img width="200" src="https://babesabouttown.com/wp-content/uploads/2010/06/chicken-pox-boy.jpg">
</p>

**Data Set Information:**

A spatio-temporal dataset of weekly chickenpox (childhood disease) cases from Hungary. The dataset consists of a county-level adjacency matrix and time series of the county-level reported cases between 2005 and 2015. There are 2 specific related tasks: County level case count prediction and nation level case count prediction.

There are 2 specific related tasks:

- County level case count prediction.
- National level case count prediction.

**Links:**

- [Chickenpox Cases in Hungary Edges](https://graphmining.ai/temporal_datasets/hungary_county_edges.csv)
- [Chickenpox Cases in Hungary Time Series](https://graphmining.ai/temporal_datasets/hungary_chickenpox.csv)


**Citing:**
```bibtex
@misc{rozemberczki2021chickenpox,
      title={{Chickenpox Cases in Hungary: a Benchmark Dataset for Spatiotemporal Signal Processing with Graph Neural Networks}}, 
      author={Benedek Rozemberczki and Paul Scherer and Oliver Kiss and Rik Sarkar and Tamas Ferenci},
      year={2021},
      eprint={2102.08100},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
### Characteristics of the dataset

The data consists of county level time series and a spatial graph which describes the spatial connectivity of the
counties. The county level time series describe the weekly number of chickenpox cases reported by general practitioners in Hungary.

The data collection covered the weeks between the January of 2005 and January of 2015 and the resulting time series has more than 500 entries for all of the counties without any missingness.

