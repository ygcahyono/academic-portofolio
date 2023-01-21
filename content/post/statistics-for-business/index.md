---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Statistics for Business (2018)"
subtitle: ""
summary: ""
authors: 
- admin
tags: ["statistics","data-analytics"]
categories: []
date: 2018-02-03T23:57:40Z
lastmod: 2018-02-03T23:57:40Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Statistics for Business (Part#1)

Hello, this is my first post of this blog! Especially in data world. This blog actually is a tool to make me remind again what i have learned. One particular reason is to refresh short-term memory of mine from my learning and working experience. First thing first, Disclaimer: This blogpost typically wont explain about deep math and list of differential formulas used for proofing something mathematically (this writer hasn’t any knowledge of them all), but more about fun things: visualization and intuitive!

Well, for this time I write about a course that i’ve finished several days ago. A Udemy course, is titled “Statistics for business analytics” by Kirill Eremenko as the author and Vitaly Dolgov as his mentor (his professional life mentor, not kinda course mentor). This blog will be explained in several part, maybe 3 or more but not less.

…

So why statistics? all the data scientist task require statistics to know how to leverage those myriad amount of data, even a data analyst surely need statistics to make their data more understandable. If you type in google “why do we have to learn statistics for data science?” you gonna get your answer there. Indeed, a data scientist must be the one who understand statistics more than programmer also understand code more than statistician as well.

This course mainly cover hypothesis testing in advanced. Even though, We know Stats has very wide coverage aspects, this course enough to help us to survive as “early entry of data scientist phase”.

In this blog Series. we try to cover 3 segments, 1 Central Limit Theorm, 2 Hypothesis Testing, 3 advanced hypothesis testing. This post we’ll talk about CLT first!

Hop onto more less serious part!

The Central Limit Theorem (CLT), and the concept of the sampling distribution, are critical for understanding why statistical inference works.

CLT is a statistical theory that given a sufficiently large of sample size from the population the mean of all those samples from the same population will be equally close to the mean of the population. Furthermore, all of the samples will follow an approximate normal distribution pattern. With the standard deviation being approximately equal to the standard deviation of the population divided by the sample’s size.

Let’s jump into example, if we have a random value of the parent distribution (population) mean = 0; std dev = 22; #of data: unknown; distribution: normal; the vis like this:

![Normal Distribution](./featured.png "Population distribution: Normal")

Assume, we don’t have any computation resource to know the mean of the enormous volume of data. but we have to know what’s the average / mean of the population. We can done this by using CLT, as it mentioned above if we have samples with sufficient number of size (30 really enough), choose randomly, and make around 200 samples (with replacements is okay) then average the result. The mean of the cumulation sample and the mean of the population will closely same!

![Continuing to Sample 200](./img-2-continuing-sample.png "Continuing to Sample 200")

The distribution of the all samples actually going to be normal distribution as well, no mater the parent population distribution’s shape.

![Sample Means](./img-3-sample-means.png "Sample Means")

One more thing: as we increase the size of the sample, the variance/standard deviations is getting lower, this is the vis: (N is size of each sample, Rej. rate: is the areas of rejection if we set p-value under 5%).

![Histogram of Z-Scores](./img-4-histogram-of-z-score.gif "Histogram of Z-Scores")

If you want to play with CLT’s dashboard created by shinny you can access here. The part#2 of the blogpost series will talk about the CLT application in the real word, and more advanced CLT foundation~.

Advice please welcome and be gentle, newbie is here :D