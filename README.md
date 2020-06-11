# Computational Alloy Design and Discovery using Machine Learning

Currently, the development of new materials such as alloys, using conventional research techniques such as empirical and stepwise approaches, is a lengthy, expensive process. 
In this project, we focus on the application of machine learning techniques on already existing experimental data relating to 5xxx series aluminum alloys to gain knowledge 
into the high dimensional relationship between alloy composition and its physical properties. The knowledge gained is used to screen generated alloy composition based on its 
corrosion resistance property. This process gives us the ability to select a handful of specific alloy composition for further experimental verification, instead of having an 
infinite number of possible compositions that cannot be verified through an exhaustive process. The results show us that a machine learning algorithm can accurately learn the 
relationship between the input alloy composition and output feature, which in this case is the material properties.

Using an algorithm to generate alloy compositions that have not yet been used in real-world applications, we generate millions of possible alloy compositions, which are then 
passed over though a screening stage to eliminate combinations of elements that are not applicable to our case. The resulting compositions after the screening process are then 
examined for validity. The screening stage is implemented as a machine learning model that has been trained on already existing 5xxx series aluminum alloys.

## Getting Started
Clone or download the repo to get started. All relevant files and data are provided.

### Prerequisites

The code is written in python 3.7.6

Required packages:

	seaborn
	sklearn
	xgboost
	pandas
	matplotlib
	numpy
	torch
	os
	random
	itertools
	math


### Installing Packages

Use the following commands to install important packages

Installing pytorch for windows with cuda

```
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
```

Installing pytorch for windows without cuda

```
conda install pytorch torchvision cpuonly -c pytorch
```

Installing pytorch for mac

```
conda install pytorch torchvision -c pytorch
```

Installing pytorch for linux without cuda

```
conda install pytorch torchvision cpuonly -c pytorch
```


Installing pytorch for linux with cuda

```
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
```

Installing xgboost

```
pip3 install xgboost
```

Installing seaborn

```
pip3 install seaborn
```

## Running the tests

The code is provided as a jupyter notebook. Each block has been run and the output recorded. 
Run each block just like any other notebook if you wish to change some parameters.
Note: Running the genetic algorithm section can take upto 3 hours

### Code output summary 

1) Comparing different ML models
2) Comparing the variation of performance of KNN model
3) Comparing the variation of performance of SVR model
4) Data visualization
5) Training and testing xgboost
6) Removing outliers
7) Comparing xgboost before and after removing outliers
8) Data generators
9) Composition output

## Author

* **Yadu Krishna Choyi**

## License

This project is licensed under the Australian National University

## Acknowledgment

* Prof. Nick Birbilis, Deputy Dean, College of Engineering and Computer Science ,Australian National University.

