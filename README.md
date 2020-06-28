# moreThanANOVA

## Why ANOVA
Once you want to compare some data between different treatments, what you learned from plenty of papers, articles and thesises is using **ANOVA (Analysis of variance)**, even we don't really know what is ANOVA.

*Quiz*: Why do you choose ANOVA? Here are probably your answers:

1. Others use it in their own works.
2. It can compare something.
3. Becasue I know why.

Howver, what others do are not always right, are they? At least, are not always suitable for any situations.

## Beyond ANOVA
Here, we don't state what is ANOVA, there are amount of articles and videos about this topic.

For what I can tell, there is an **premise** of ANOVA, in fact it is a premise for all t-test family, is **Normal Distribution**(also Known as **Gaussian Distribution**). Once your data do not meet normal distribution, maybe you want to transform them, like log(x+1), square-root, log, etc.

However, we are not always lucky dogs, literally, it even never works for me in my current research.

Gernerally, we choose nonparametric tests, the most famous nonparametric tests to compare data between two treatments are **Mann–Whitney U test**, while across triple or more treatments, **Kruskal-Wallis rank sum test** are often performed.

Their are conceptions about signed-rank test and signed-rank sum test. We also don't state what are these conceptions, but I highly recommand you to Google them before you choose a test. Here is a article that posted by **Stats and R** entitled [Wilcoxon test in R: how to compare 2 groups under the non-normality assumption](https://www.statsandr.com/blog/wilcoxon-test-in-r-how-to-compare-2-groups-under-the-non-normality-assumption/).

Besides, the permutation test is also used as a fancy method to evaluate the significant level especially for data with unknown distribution. For more information, there is an article from [R-Bloger](https://www.r-bloggers.com/what-is-a-permutation-test/), and here is [another Chinese article](https://www.r-bloggers.com/what-is-a-permutation-test/) about it.


## Features
- [x] Data View
- [x] Data Distribution Detect
  - [x] Data Distributions
  - [x] Automatically determine methods
  - [x] Data density plot
- [x] Significant Comparisons
  - [x] Significant Table
  - [x] Mean, Median and Sig-Level
  - [x] Post Hoc test plot

## How to use it?

### 1. EZ way
[Click here](https://hanchen.shinyapps.io/moreThanANOVA/). moreThanANOVA is hosted at [Shinyapps.io](https://Shinyapps.io).

### 2. Hardcore way
To make sure that you can control everything, you are welcomed to [fork my code](https://github.com/womeimingzi11/moreThanANOVA/fork) to your own repo (and leave me a star please).

Then what you can do is to oepn `moreThanANOVA.Rproj` file in RStudio, following open `app.R` file, install all the packages which will be loaded.

At the least, click `run.app` at the right top of the code editor panel, **rdaWithStep** will run locally.

![](resource/figure/runApp.png)

#### Upload Data
You can upload your file with following structure.
![](resource/figure/table_str.png)

## Privacy Statements
We gurantee that all your data won't be kept once you leave the Shiny app. There is no code and won't have any code to record your cilentID, uploaded file or any other data.

## Known Issues
You tell me.

## Contact Me
You are welcomed to commit any feature about this and even any other features in my [repo on GitHub](https://github.com/womeimingzi11/moreThanANOVA).

You are also welcomed to visit my [Blog (in Chinese)](https://womeimingzi11.github.io) or contact me by [mail](mailto://chenhan28@gmail.com).