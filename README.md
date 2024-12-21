java c
Math Stats
Practice Final
1. Suppose X0 = 0 and X1, · · · , Xn are given by the following Gaussian autoregressive process i.e. the AR(1) model
Xi = θXi−1 + εi
with θ ∈ [0, 1) unknown, and the errors εi ∼ N (0, σ2) i.i.d. with σ2 > 0 known.
(a) Write down the log-likelihood function for the unknown parameter θ.
(b) Find θˆMLE.
(c) Find the least squares estimate θ
2. Suppose you have a true model
y = αeβx+ϵ
where ϵ ∼ N (0, σ2)
and the following data
x    y
2    4
3    7
5    8
(a) Find the least squares estimates ˆα and β
(b) Construct a 95% Confidence Interval for β.
3. X1 . . . Xn ∼ exp(θ/1) IID.
(a) Calculate the MLE θˆ
(b) Calculate the bias, variance, MSE, and efficiency of θˆ
(c) Show that ˆθ →pθ/1, ie. that is it consistent.
(d) Calculate the exact and asymptotic sampling distribution of θˆ
4. A coin is thrown independently 10 times to test the hypothesis that the probability of heads is 2/1 versus the alternative that the probability is 10/1. The test rejects if either 0 or 10 heads are observed.
(a) What is the significance level of the test?
(b) What is the power of the test?
5. In a famous sociological study called Middletown, Lynd and Lynd (1956) administered questionnaires to 784 white high school students. The students were asked which two of ten given attributes were most desirable in their fathers. The following table shows how the desirability of the attribute ”being a college graduate” was rated by male and female students. Did the males and females value this attribute differently?
                                                            Male                        Female
Mentioned                               86                                55
Not Mentioned                   283                            360
6. Suppose that in the model yi = β0 + β1xi + ei, the errors have mean zero and are independent, but Var (ei) = w12σ2, where the ρi are known constants, so the errors do not have equal variance. This situation arises when the yi are averages of several observations at xi; in this case, if yiis an average of niindependent observations, wi2 = 1/ni (why?). Because the variances are not equal, the theory developed in this chapter does not apply; intuitively, it seems that the observations with large variability should influence the estimates of β0 and β1 less than the observations with small variability.
The problem may be transformed as follows:
w−1iyi = wi−1β0 + wi−1β1xi + wi−1ei
Find the least squares estimate.
7. n1 people are given treatment 1 and n2 people are given treatment 2 . Let X1 be the number of people on treatment 1 who respond favorably to the treatment and let X2 be the number of people on treatment 2 who respond favorably. Assume that X1 ∼ Binomial (n1, p1) X2 ∼ Binomial (n2, p2). Let ψ = p1 − p2.
(a) Find the MLE ψˆ for ψ.
(b) Find the standard error of ψˆ.
(c) Suppose that n1 = n2 = 200, X1 = 160 and X2 = 148. Find ψˆ. Find an approximate 90 percent confidence interval for ψ.
(d) Can we say one treatment is more effective than the other?
(e) Using the prior f (p1, p2) = 1, find a posterior given X1, X2.
(f) What if n1 = n2 = 200 and X1 = 20, X2 = 180?<代 写Mathematical Statistics Practice Final
代做程序编程语言br>8. Phillips and Smith (1990) conducted a study to investigate whether people could briefly postpone their deaths until after the occurrence of a significant occasion. The senior woman of the household plays a central ceremonial role in the Chinese Harvest Moon Festival. Phillips and Smith compared the mortality patterns of old Jewish women and old Chinese women who died of natural causes for the weeks immediately preceding and following the festival, using records from California for the years 1960-1984. Conduct to different tests to compare the mortality patterns shown in the table. (Week -1 is the week preceding the festival, week 1 is the week following...)
Week                       Chinese                       Jewish
-2                                          55                            141
-1                                        33                               145
1                                        70                               139
2                                           49                              161
9. Example B from Chapter 9 Section 5 in the textbook. Consider the following data
Value                            0        1        2        3        4        5        6        7        8        9        10        19
Frequency                    56       104       80       62       42       27    9             9        5       3       2        1          
Use three different test statistics to see if this data follows a Poisson distribution.
10. You collect data from one population and you want to test if the data follows a particular distribution. What test would you run in the following scenarios:
(a) The data is categorical (or discrete) and can only take on two values.
(b) The data is categorical (or discrete) and can take on many values.
i. You wish to test for the distribution (ie. nonparametric test).
ii. You wish to test for a parameter estimate (with asymptotically normal sampling distribution).
(c) The data is (continuous) numerical.
i. You wish to test for the distribution (ie. nonparametric test).
ii. You wish to test for a parameter estimate (with asymptotically normal sampling distribution).
11. You collect data from two populations and want to compare the distributions for both populations:
(a) The data is categorical and both populations can only take on two values.
i. Data is unpaired.
ii. Data is paired
(b) The data is continuous:
• Data is unpaired
– Populations follow normal distribution.
– We want to compare the unknown distributions.
• Data is paired
– Populations follow normal distribution.
– We want to compare the unknown distributions.
(c) The data is categorical and both populations can take on multiple values.
(d) What test would you run if you wanted to compare the distributions of multiple populations?
12. You collect data from one population and want to test if two characteristics of the population affect each other:
(a) Both features can only take on two values.
(b) One feature is numeric (and continuous), one feature can only take on two values.
(c) Both features are numerical (and continuous).





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
