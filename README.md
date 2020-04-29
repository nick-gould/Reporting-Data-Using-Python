# Reporting-Data-Using-Python
Communicating data using Python in a Jupyter notebook

# Reporting and Communicating Data Using Python

A lot of people think the work of a Data Scientist or someone working in a data role is to be able to spin up a [Apache Hadoop](https://hadoop.apache.org/) cluster and using [Apache Spark](http://spark.apache.org/) to spend 12 hours fitting an [XGBoost](https://xgboost.readthedocs.io/en/latest) model. This may be true some of the time, but really [80% of time is spent preparing data](https://www.forbes.com/sites/gilpress/2016/03/23/data-preparation-most-time-consuming-least-enjoyable-data-science-task-survey-says/).

Neither of these are topics for today. I want to talk about communicating data. All the effort put towards working with data is wasted if nobody ever uses it. If decisions are to be made with data, it first needs to be communicated\!

This will focus on [Descriptive Statistics](https://en.wikipedia.org/wiki/Descriptive_statistics), something happened and we want to understand it, but the same ideas hold true for [Predictive Statistics](https://en.wikipedia.org/wiki/Predictive_analytics) or [Prescriptive Statistics](https://en.wikipedia.org/wiki/Prescriptive_analytics).

These same concepts are at play regardless of platform being used, be it Python, R, Scala, Excel, JMP, Minitab, SPSS, etc.

To discuss:
* Always plot your data
* Reporting confidence intervals and p-values
* Some neat jupyter tricks (interactivity, HTML, hide code)

Other things to consider:
* Consistency across roles, multiple Data Scientists and Analysts should use similar (if not the same) methods, which should also be available to other technical persons who also need to work with data
* Know your audience, what makes sense for communicating with other Data Persons, Technical Persons, Business Persons, and the general public aren't always the same thing
* Label and scale your axes, one of the "best" ways to lie to people with data is to misrepresent it with unlabeled axes or messing with the scale of the axis
* Colorblindness is fairly common, keep this in mind when selecting colors
