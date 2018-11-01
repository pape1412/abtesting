# ABTesting
A simple Python package for evaluating A/B tests.

## Intro
The idea behind creating this package was to provide a __means for evaluating A/B tests__ which is free of dependencies such as ```scipy```. Despite that I've wanted to explore ways of developing my own Python package. As I work a lot with A/B tests which involve conversion events, I thought a simple two sample __Z test__ for the equality of proportions would be a good starting point. Unfortunately, this is the __only__ testing method included in this package so far. However, I will continue to add more A/B test evaluation methods in the future.

## Installation
The package installation can easily be done from the command line with
```$ pip install abtesting```
The package doesn't depend on any but standard Python libraries such as ```math```.

## Files
The following files are inluded in this package:
- ```ABTest.py``` includes classes and functions for creating test groups and using special functions
- ```ZTest.py``` included classes and functions for performing Z test

## Acknowledgements
Large parts of the core functionalities of this package would not have been there without sources like [Wikipedia](https://www.wikipedia.org) or [Stackoverflow](https://stackoverflow.com) and I've tried to include some sources within the code as possible.
