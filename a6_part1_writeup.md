# Assignment 6 Part 1 - Writeup

**Name:** _Cristian__Jacome__  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:** The R^2 score informs us how accurate the model shows the different level of variation in student scores. Additionally, to measures the change in scores by making a predication based on the change in hours studied.  If R^2 is near 1, it suggest that the model predicts the data extremely well and that number of hours studied influences scores. However, if R^2 is close to 0 it means the relationship and prediction between hours studied and scores is not accurate.




---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:** MSE in plain English tells us the error amount in squared points(how much the model is off by when predciting hours studied to scores earned). We sqaure the errors because makes the errors positve, preventing them from canceling out. Additionally, we sqaure the errors to show the model that bigger mistakes make larger errors, reinforcing them to make less errors. 




---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:** I would be extemely cautious because the maximum hour studied in the dataset was 9.6. Since the 10 hours is outside the data range linear regression wouldn't work as well. This would create something I learned in middle school called extrapolation, which could give a wildly wrong prediction. 




---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:** After looking at my scatter plot, the relationship between hours studied and test socres is strong(points closed otgether), linear(trend looks like a straight line), a positive(trend line increases as hours studied increases).




---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. 504 Plan/ IEP 
2. Sleep/ mental health
3. Quality of Note taking


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**
We slpit our data into training and testing sets to train the model with data so that it can get familiar with itself. Then we implement testing data to test if the model works on newly introduced datat. I we trained and tested on the same data the model would memeorize the answers, rather than performing its functions.  



---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**

The most challenging part for me was remember what linear regression was. But once I heared Mr.Berg presentation I remember that linear regression is a model that predicts/estimates the relationship between x and y variables. 


---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**

Relationship between price of house in correlation to sqaure footage per house. 
Feature(x) = Sqaure footage per house
Feature(Y)= Price of the house 
This relationship might be linear because the bigger a house is(square footage) the more expensive the listing of the house will be. 


---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
