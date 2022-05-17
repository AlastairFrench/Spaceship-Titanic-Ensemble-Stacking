# Spaceship-Titanic-Ensemble-Stacking

Python notebook for my submission to the Kaggle datascience competition "Spaceship Titanic". For ease of reading I have split up my submission into different repositories for the different sections of my data science framework. In this section I used an ensemble stack to try and harness the capabilities of a range of well-performing models to make predictions that have better performance than any single model in the ensemble.

I prepared the training dataset for the meta-model using k-fold cross-validation of the base models, where the out-of-fold predictions were used as the basis for the training dataset for the meta-model.

In this repository I have also included the cleaned train and test data from my Spaceship-Titanic-Data-Wrangling repository, as well as the MLA prediction scores from my Spaceship-Titanic-Modelling repository. 

From Kaggle: 

"Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

Help save them and change history!"
