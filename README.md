# Airbnb Data Analysis

## Motivation

This repository contains an analysis of Airbnb apartments in Seattle. The analysis was
carried out as the first project of [Udacity Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025).
The main motivation is to give people that plan to visit Seattle an understanding of
the availability of Airbnb apartments, when is the best time to travel and how much they
should plan to spend for an apartment.

This project follows the CRISP-DM Process (Cross-Industry Standard Process for Data
Mining) which contains the following steps:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation
6. Deployment

The data basis comes from the vacation rental company Airbnb which covers:

- all Airbnb listings in Seattle as of 2016-01-04
- all Airbnb reviews for these listings as of 2016-01-03
- the daily Airbnb availability of these listings for entire 2016

The project addresses a number of business questions and real-world use cases:

1. Is there an upward trend of new Airbnb listings in Seattle?
2. What are the busiest times of the year to visit Seattle and how do prices vary?
3. Can we estimate the price for a common type of accommodation to see how much we
   should plan to spend?

## Libraries

The following external Python libraries were used throughout this project:

- pandas
- NumPy
- Matplotlib
- seaborn
- scikit-learn

## Results

### 1. Is there an upward trend of new Airbnb listings in Seattle?

The answer is clearly yes! When planning a trip to Seattle, you can rely on a variety of
different places to stay. This number has increased tremendously over time - from 4 in
2008 to almost 1,000 in 2015!

There are plenty of different opportunities for a trip for everyone: be it in a dorm,
in a loft, or even on a houseboat! Try to consider all the options to make your stay a
really special one.

### 2. What are the busiest times of the year to visit Seattle and how do prices vary?

According to the availability of Airbnb accommodations, Seattle turns out to be most
busy in January, February and July. In these months, the availability is up to 17%
below the annual average. In contrast, most accommodations are available in March,
October and December.

The prices of accommodations do not behave contrary to their availability.
Interestingly, the prices rather follow a trend similar to the temperature throughout
the year.

If you want to make a good deal in terms of availability, price and weather conditions,
you might consider planning a trip to Seattle in March. Here, the ratio between those
three factors seems to be quite tourist-friendly!

### 3. Can we estimate the price for a common type of apartment to see how much we should plan to spend?

Using a very simple prediction model, which is able to explain at least 60% of the
variability in the price, we can try to find out what is actually a fair price for
accommodation.

For a private loft in Seattle Downtown with the following characteristics:

- 2 bedrooms,
- 4 beds,
- 1 bathroom and
- $30 cleaning fee,

this model predicts about 165$ per night so this is what you might roughly plan for your
stay in an apartment like this.

If you are rather a low-budget traveler instead or just need some place to stay in order
to get new energy for your next adventure in and around Seattle, you could consider
renting a shared room, a private room, or a bed in a dorm since this has a negative
effect on the price.

Use the prediction of the accommodation price as a first benchmark. Of course, there is
much more to consider, such as the furniture or the rating of the host - and you might
be willing to pay a bit more for that - but still, it's a good starting point.

## Acknowledgments

- [Kaggle link to Airbnb data](https://www.kaggle.com/airbnb/seattle)
- [Udacity link to Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025)