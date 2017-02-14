### ***Project 2 Feedback***

***Nico Van de Bovenkamp***
***

**Overall** Good work! You were very concise, and clear, in your exploratory analysis! You also made very good use of the plotting functions in matplotlib, in particular with the density plot that you made.

* **Q.9** This question could use a bit more detail and attention. Why is the distribution not normally distributed? Is it okay that is slightly off from being normally distributed? How could you *test* for that? You answer some of this in **Q.10**, but be a bit more explicit for this part. In the end, it is not quite normally distributed, but that is okay as far as our models are concerned. However, in our analysis, if we wanted to mention why our model may prove to have some error (which it will), then this is some potential source of error.
* **Q.13** Don't forget to include the steps you took to drop missing values, or any other data manipulation you may perform!

**Bonus** Nice work on the bonus, and thank you for taking a whack at it! When you are imputing missing values, we could impute a 0, however that would heavily skew our models as you are putting some downward bias into the distribution/model. Think: how can you impute data so that your model will benefit and/or not be biased by the data you are imputing? For some further reading, [check out this guide!](http://chrisalbon.com/python/pandas_missing_data.html)
