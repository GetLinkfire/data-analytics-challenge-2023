# Linkfire Data Analytics Challenge

## Task

The [`traffic.csv`](https://drive.google.com/file/d/1oTJmeBMly1TPOzpby-8c5bZ2cctELUrb/view?usp=sharing) file and the [`traffic.db`](https://drive.google.com/file/d/1LkPAHTELcFKcEhGSRr7nk7FaDbW_rt_T/view?usp=sharing) SQLite database contain the same web traffic data ("events") from a few different pages ("links") over a period of 7 days including various categorical dimensions about the geographic origin of that traffic as well as a page's content.

Our goal is to understand this traffic better, in particular the volume and distribution of events, and to develop ideas how to increase the links' clickrates. With that in mind, please analyze the data using plain SQL statements as well as the Python [Pandas](https://pandas.pydata.org) and [SciPy](https://docs.scipy.org/doc/scipy/) libraries where indicated, providing answers to the following questions:

1. [SQL + Pandas] How many total pageview events did the links in the provided dataset receive in the full period, how many per day?
2. [SQL + Pandas] What about the other recorded events?
3. [SQL + Pandas] Which countries did the pageviews come from?
4. [SQL + Pandas] What was the overall click rate (clicks/pageviews)?
5. [Pandas] How does the clickrate distribute across different links?
6. [Pandas & SciPy] Is there any correlation between clicks and previews on a link? Is it significant? How large is the effect? Make sure to at least test for potential linear as well as categorical (think binary) relationships between both variables.

## Presentation

Please think about how to best convey this information to both technical and commercial stakeholders and prepare 3 different types of reports:

1. A low-level, ad-hoc analysis for your product team (product manager + engineers), including code and results (e.g. in a [Jupyter Notebook](https://jupyter.org))
2. A high-level presentation for commercial stakeholders, focussing on narrative and visualizations (e.g. with [Google Slides](https://docs.google.com/presentation/))
3. A mockup for a live dashboard highlighting relevant metrics (e.g. with [Miro](https://miro.com) or [Figma](https://www.figma.com))

## Additional notes

We expect you to spend 2-3 hours to prepare these reports. Please work on them in the displayed order. In case you are not able to finish everything within 3 hours, this is not a problem and we will just talk through the rest. Besides, please don't hesitate to contact us in case you have any questions.
