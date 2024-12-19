# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
Models acuracy was 0.66. Since the data was not scaled, the accuracy was a lot lower.
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
It was about 0.85-0.9. It is accurate enough for the given case.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
Most of the predicted and actual results were the same except for a couple. Yes, most of the incorrect predictions were 0 while the actual species was 1.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No
