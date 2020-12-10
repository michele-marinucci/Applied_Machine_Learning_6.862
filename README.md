# Applied Machine Learning (6.862), Final Project: Predicting Returns in the US Equity Markets
### Michele Marinucci, Henry Donnelly, and Raphael Bakobza. 

## Repository overview
In this repository, you may find:
1) this README file
2) the pdf file with our final write-up
3) the code file in ipynb, to be run as a jupyter notebook
4) please refer to this Drive folder to have a look at the data: https://drive.google.com/drive/folders/1fxaF4_XCFfYsDG54xsLIn8zrbcy9u-8Y?usp=sharing

## Abstract
This paper builds upon a Machine Learning contest proposed by Qube Research Technologies
(QRT), a quantitative hedge fund. Using historical data in the US equity market spanning a period
of 20 days across different dates, we attempted to
predict the one-day horizon stock return. More
specifically, we built a classification model for
the sign of such stock returns. We evaluated
the performance of our models through a score
based on accuracy (i.e. percentage of correct predictions). QRT provides a testing data base as
well as a benchmark performance with a score of
51.31%. After engineering the right features, fitting a wealth of machine learning models and tuning their hyperparameter following state-of-theart techniques, our final model beats QRT’s benchmark though a random forest yielding an accuracy
of 51.43%. As a note to the reader, both QRT’s
benchmark model and our model may seem to be
inaccurate predictors, nevertheless these results
are fairly remarkable if one considers the random
walk nature of stock markets. In fact, through
sheer repetition and volume, a model that’s right
51-52% of the times may translate into significant
profits on the financial markets over time, though
not necessarily beating similar trading strategies
in terms of Sharpe ratio or return-risk ratio.
