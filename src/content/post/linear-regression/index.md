---
title: "LINEAR REGRESSION MODELS WITH DEPENDENT OBSERVATIONS"
date: 2017-10-18T09:36:19+08:00
draft: false
---

# LINEAR REGRESSION MODELS WITH DEPENDENT OBSERVATIONS

## Introduction to Time Series Analysis

- autoregression model

  ![](26.JPG)

- Stationarity

  - strictly stationarity

  ![](27.JPG)

  a strictly stationary process may not have finite moments.

  However,if moments and cross-moments of $${Z_t}$$exist, then they
  are time-invariant when $${Z_t}$$ is strictly stationary.

  - [N-th order stationarity]

  ![](28.JPG)

  - [Weak Stationarity]

    ![](29.JPG)

  - [White Noise]

    ![](30.JPG)

    ![](31.jpg)

    ![](32.jpg)

    ![](42.jpg)

    ![](43.jpg)

    ![](34.jpg)

    **关系：**

    ![](44.jpg)

    ​

    ![](35.jpg)

    ![](45.JPG)

    ![](36.jpg)

    ![](37.jpg)

## Framework and Assumptions

- assumptions

![](38.JPG)

- Consistency of OLS

  与之前相同，唯一不同就是在应用LLN时，iid替换为by the WLLN for ergodic stationary processes.

- Asymptotic Normality of OLS

  与之前相同，唯一不同就是在应用CLT时，iid替换为By the CLT of stationary ergodic MDS processes

- Asymptotic Variance Estimator for OLS

  ![](39.JPG)

  ![](40.JPG)

  ![](41.JPG)

  其他都一样，不同之处在于把iid替换成theWLLN for ergodic stationary processes和MDS

## Hypothesis Testing