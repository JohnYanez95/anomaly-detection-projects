# Credit Card Fraud Detection

If you ever had your debit/credit card information stolen, then this will provide some insight on how such instances are detected.

## Table of Contents

- [Credit Card Fraud Detection](#project-title)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Dataset](#dataset)
  - [Dependencies](#dependencies)
  - [Usage](#usage)
  - [Results](#results)
  - [License](#license)

## Overview

The goal of this project is to find an effective means to determining fraud among charges applied to a debit/credit card.

We will explore multiple techniques, that include:
* Supervised Learning Techniques,
* Unsupervised Learning Techniques,
* and Semi-Supervised Learning Techniques

Logically it would make sense to apply occam's razor and only use Supervised Learning Techniques, but, to state again, I wish to demonstrate knowledge of multiple techniques.

In the real world, data doesn't always come with known labels and will have to be mined based on a very selected few examples; hence the desire to utlize Unsupervised Learning Techniques and Semi-Supervised Learning Techniques.

## Dataset

In this instance, we will be utilizing the Credit Card Fraud Detection dataset from:
* https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Which was sourced from a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.

The following is known about the dataset:
* The dataset contains transactions made by credit cards in September 2013 by European cardholders.
* This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
* The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are primarily the results of a PCA transformation. 
* Due to confidentiality issues there is no other features among the data in regards to what was made into the PCA.

Features include:
* Principal Components: V1, ..., V28;
* Time: contains the seconds elapsed between each transaction, and the first transaction of the dataset;
* Amount: the transaction Amount;

Targets include:
* Class
	- 0 for non-fraudlent
	- 1 for fraudlent

## Dependencies

[List any dependencies required to run the code, including versions if applicable.]

## Usage

[Describe how to run the code and any important parameters or arguments that need to be set.]

## Results

[Provide an overview of the results achieved in the project, including any metrics used to evaluate performance.]

## License

[Specify the license under which the code is released.]
