# Airbnb Data Analysis

## Motivation

This repository contains an analysis of Airbnb apartments in Seattle. The analysis was
carried out as the first project of [Udacity Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
The main motivation is to give people that plan to visit Seattle an understanding of
the availability of Airbnb apartments, when is the best time to travel and how much they
should plan to spend for an apartment.

Airbnb provided the data which covers:

- all Airbnb listings in Seattle as of 2016-01-04
- all reviews for these apartments as of 2016-01-03
- the daily availability of these apartments for entire 2016

The project addresses a number of business questions and real-world use cases:

1. Is there an upward trend of new Airbnb listings in Seattle?
2. What are the busiest times of the year to visit Seattle and how do prices vary?
3. Can we estimate the price for a common type of apartment to see how much we should
   plan to spend?

## Libraries

The following external Python libraries were used throughout this project:

- pandas
- NumPy
- Matplotlib
- seaborn
- scikit-learn

## Results

### 1. Is there an upward trend of new Airbnb listings in Seattle?

Yes, there is one! Seattle has become more and more present on Airbnb over time. The
number of new listings in Seattle has increased from 4 in 2008 to almost 1,000 in 2015.
There is plenty of different opportunities for a trip for everyone: be it in a dorm, in
a loft, or even on a houseboat!

### 2. What are the busiest times of the year to visit Seattle and how do prices vary?

According to the Airbnb data, Seattle turns out to be **most busy in January, February and
July**. In these months, the availability is up to 17% below the annual average. In contrast,
most apartments are available in March, October and December.

The average price for an apartment increases steadily over the year until it reaches a
**peak in July**. After July, the prices decrease again.

If you want to make a good deal, you should consider planning a trip to Seattle in March. Here,
the ratio between apartment availability and apartment prices are most tourist-friendly.

### 3. Can we estimate the price for a common type of apartment to see how much we should plan to spend?

You ever wanted to know what is actually a fair price for an apartment? Using a very
simple prediction model, which is able to explain at least 60% of the variability in the
price, we try to answer this question. For a private loft in Seattle Downtown with
2 bedrooms, 4 beds, 1 bathroom and $30 cleaning fee, this model predicts about 165$ per
night so this is what you should plan for your stay in an apartment like this. If you
are a low-budget traveler instead, you could consider renting a shared room, or a bed in
a dorm since this has a negative effect on the price

Please keep in mind the following: As shown above, the prices vary during the year, and
the prediction model explains only 60% of the variability in the price which there are
still plenty of factors which are not considered here.

## Acknowledgments

- [Kaggle link to Airbnb data](https://www.kaggle.com/airbnb/seattle)
- [Udacity link to Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025)