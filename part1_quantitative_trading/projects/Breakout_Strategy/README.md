# Project: Breakout Strategy

**Aim:** Implement a breakout trading strategy and use backtesting to estimate its profitability.

**Topic**: Advanced Quantitative Trading.

## Overview
* Creating and backtesting a breakout trading signal. Outliers are removed in order to ensure a robust backtesting process.
* The dataset is a set of end-of-day stock prices that comes from [Quotemedia](http://www.quotemedia.com/).

## Concepts
* Identifying long and short breakout trading signals over various time windows.
* Filtering out repeated long/short signals inside each time window.
* Using the Kolmogorov–Smirnov test to identify outliers.
* Computing signal return only after removing all outliers that were discovered.

## Grading and Evaluation 

* [Here](https://review.udacity.com/#!/reviews/2298660)
