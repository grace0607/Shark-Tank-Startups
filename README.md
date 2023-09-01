# Will I be Disadvantaged as a Female Startup Founder? Here are Some Suggestions from Shark Tank US Data Over the Years
*Click [here](https://github.com/grace0607/Shark-Tank-Startups/blob/main/Shark_Tank_Startups.ipynb) to check out the full project in this repository!*

Ever had a brilliant business idea that got you all excited about founding a startup of your own? Thought about pitching your idea on Shark Tank or to potential investors? Particularly for female-identifying folks, did you ever feel that you were at a disadvantage compared to your male counterparts?

For those of you who haven't heard about [Shark Tank](https://abc.com/shows/shark-tank), it's a US TV series that brings startup founders together to pitch their businesses to a panel of five investors or "sharks", who decide whether to invest in their companies.

## My Questions
In my project, I am curious about whether female contestants (founders) end up settling for less favorable deals (investments) compared to male contestants. Apologies in advance for being gender binary- I am working with the two groups for the purpose of analytical simplicity!

So my questions are:

1. Is there a difference in the final deal amount, deal equity, and deal valuation that male vs. female contestants end up winning on average?

2. What about the original ask amount, original offered equity, and requested valuation before the final judging?
*If so, is that where the difference in final deal terms stems from?

*Quick blurb on VC investments*

What makes a VC deal favorable from the perspective of an entrepreneur? In general, the goal is to get the most amount of funding for the least percentage of equity. This ensures that your company is getting a high valuation. For example, if the entrepreneur is getting $100,000 for 10% equity, $100,000 is 10% of the company's valuation. So the company is being valued at $1 million ($100,000 x 10). The lower the equity and higher the funding amount, the higher the valuation. You can read more about it [here](https://technical.ly/startups/valuation-meaning-shark-tank/).

## My Hypotheses
I hypothesize that there will be a difference in the final deal terms (deal amount, deal equity, and deal valuation) between male and female contestants.
However, I hypothesize that there will NOT be a difference in the original/requested deal terms that contestants pitch for initially.
Perhaps female contestants end up settling for less favorable deals because they negotiate less aggressively than their male counterparts.

## The Data
I use a [Shark Tank US dataset](https://www.kaggle.com/datasets/thirumani/shark-tank-us-dataset) that has data from season 1 to season 12. It contains information about the startup, industry, entrepreneur's name, gender, city as well as deal statistics such as original and final deal amount, deal equity, etc. It also contains information about amount invested per "shark" (or judge) among many others. The dataset contains 52 columns and 1006 rows.
