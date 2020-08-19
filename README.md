# Recommendations with IBM

## Table of Contents
1. [Description](#description)
2. [Getting Started](#getting_started)
	1. [Dependencies](#dependencies)
	2. [Installing](#installing)
	3. [Additional Material](#material)
3. [Authors](#authors)
4. [License](#license)
5. [Acknowledgement](#acknowledgement)

<a name="descripton"></a>

## Description

This project analyzes the interactions that users have with articles on the IBM Watson Studio platform. The project aims to make recommendations for users on the IBM platform about new articles that they might like. 

The Project is divided in the following Sections:

1. Exploratory Data Analysis 
2. Rank Based Recommendations
3. User-User Based Collaborative Filtering
4. Content Based Recommendations
5. Matrix Factorization 

<a name="getting_started"></a>
## Getting Started

<a name="dependencies"></a>

### Dependencies
* Python 3.5+ (I used Python 3.8)
* Machine Learning libraries: NumPy, SciPy, Pandas, Scikit-Learn
* Natural Language Process libraries: NLTK

<a name="installing"></a>

### Installing
Clone this GIT repository:
```
git clone https://github.com/lng15/IBM-Recommendations
```
<a name="material"></a>

### Additional Material

**data** folder contains dataset which fetched from IBM Watson Studio:

- **articles_community.csv** dataset contains articles information
- **user-item-interactions.csv** dataset contains users information, as well as users-articles interactions.

There are two notebooks in this repo:

1. **Recommendations_with_IBM.ipynb** : the main notebook which contains all Sections mentioned in the Description.
2. **Content Based.ipynb** : the extra notebook which is made as another way to recommend content to users. It is not required to finish the project and it will be improved in the future. However, its result can be used to compare to the approach in the main notebook above.

<a name="authors"></a>

## Authors

* [LN](https://github.com/lng15)

<a name="license"></a>

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

<a name="acknowledgement"></a>

## Acknowledgements

* [Udacity](https://www.udacity.com/) for giving me a chance to work on the project
* [IBM](https://dataplatform.cloud.ibm.com/login) for providing the permission to use data on the platform

<a name="screenshots"></a>

