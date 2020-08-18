
# portfolio management using machine learning
-------MOVING_AVERAGE WITH BOLLINGER BANDS------------
MOVING AVERAGE: moving average is the average of a certain period window in 9 or 21 and the window is rolling through the series
BOLLINGER BANDS: These bands are the standard deviation of moving average with 20%
@@@@@@@Trading stratagy----if a stock fall to the lower bollinger band and starts to come to average line then we should buy it. if a stock rises to the upper bollinger band and stats to come to average line then we should sell it.
Inflection points: when price is outside of bollinger bands
--------log return and normal return-----------
log return: log value of present value to previous data value
normal return: present value tp previous data value to minus 1
why log return?????????? 1)log returns can be interpreted as continously compound returns 2)log returns are time_additive.the multi period log return is simply the sum of single period log terms 3)the use of log returns prevents security prices from become negitive in modules of security returns 4)For many purpose,log returns of security can be reasonable modeled as distribution all to normal distribution 5)when returns and long returns are small their returns are approx. equal 6)logarithmic can help make an algorithm more numerically stable.
----------T STATISTICS OR T TEST----------- T test are implimented on continous type values sample If the sample is greater than 30 t test is implimented else z test is implimented there are two types of t tests : 1)1 sample t-test 2)2 sample t-test hypotisis0(H0) :- It is not different ------> null hypotisis hypotisis1(H1) :- It is different ----------> alternative hypotisis
alpa(a) = 0.05 ------> means 5% of data p ------->significant value
1)1 sample t-test: comparing the total mean with the sub sample mean of the sample and calc the p value if p<a(i.e., p<0.05) ----->null hypotisis is violated if p>a -------->null hypotisis is accepted
1)2 sample t-test: comparing the total mean of one sample with the other sample mean and calc the p value if p<a(i.e., p<0.05) ----->null hypotisis is violated if p>a -------->null hypotisis is accepted
-------covariance and correlation---------- covariance: x is increasing and y is increasing = +ve value from the formula x is increasing and y is decreasing = -ve value from the formula covariance is used to know the direction and correlation is used to know the drection and the how much magnitited
correlation: correlation always lies between -1 - 1
if correlation =1 ----->x and y features are same so we can consider only one between them if correlation = -1 --->x and y features are opposite if correlation = 0----->x and y dont have any same features if -1 < correlation < 0---> x and y have negitve slope and have less opposite variation if 0< correlation <1 -----> x and y have positive slope and have less varaiation
