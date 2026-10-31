# Group 4 – Module 08 Lab Reflection
**Course:** ITAI 1371 – Introduction to Machine Learning  
**Lab:** Module 08 – Bias-Variance Tradeoff and Overfitting  
**Group:** Group 4  

---

## Member 1 – Patrick Rostand Gandjouon Tchassem

### My Reflection

This lab helped me understand the difference between underfitting and overfitting better. Before working on the lab, I knew that a machine learning model could be too simple or too complicated, but I did not fully understand how that affects predictions. After running the code and looking at the graphs, it started to make more sense.

One thing I found interesting was comparing the three polynomial models. The degree 1 model was just a straight line and could not follow the pattern in the data. The degree 4 model followed the pattern better, while the degree 15 model was more complicated and started following small changes in the data. This helped me see that making a model more complex does not always mean it will perform better.

The learning curves were another important part of the lab for me. I noticed that the degree 1 model had low scores because it was too simple to learn the pattern. The degree 15 model had a big difference between its training and validation scores. Some of the validation scores were extremely low, which showed me that a model can work well with training data but struggle when tested on different data.

I also learned that we cannot judge a model only by how well it performs during training. We need to check how it performs on data it has not seen before. Overall, this lab gave me a better understanding of bias, variance, and why finding the right model complexity is important in machine learning.

---

## Member 2 – saimi manasiya
In this lab, I learned about the bias-variance tradeoff and how model complexity affects the performance of machine learning models. I understood the difference between underfitting and overfitting by comparing polynomial regression models with degrees 1, 4, and 15. The degree 1 model was too simple to capture the pattern in the data, while the degree 4 model provided a better fit. The degree 15 model was more complex and showed signs of overfitting because it performed better on training data but struggled to generalize to unseen data.

I also learned how learning curves help us understand a model’s performance by comparing training scores and cross-validation scores as the number of training examples increases. The degree 1 model showed signs of underfitting because it struggled to learn the underlying pattern even with more training data. The degree 15 model showed a larger difference between training and cross-validation performance, indicating high variance and poor generalization. This activity helped me understand why choosing the right model complexity is important in machine learning.

Overall, this lab improved my understanding of polynomial regression, learning curves, underfitting, overfitting, and generalization. I learned that a complex model is not always the best model and that the goal is to find a balance between bias and variance. These concepts will help me understand how to build machine learning models that perform well on both training data and new, unseen data.


---

## Member 3 – Kenneth Kouokam

For Module 08, my assigned role is Synthetic Data and Initial Exploration. The main idea I take from
this setup is that understanding the data comes before deciding how complicated a model should be.
The lab uses a sine function with added random noise, which makes the distinction between the
underlying relationship and individual observations easier to understand. The target is numerical, so
this is a regression problem even though the pattern is curved.

The added noise gives the exercise a useful purpose. Without it, the observations would sit exactly
on the sine curve. With it, individual points can be above or below the underlying pattern. This helps
me understand why matching every training point is not necessarily the goal. A very flexible model
might follow random fluctuations that will not appear in another sample. I can connect this to
overfitting: a model can look successful on the data it has already seen while being less reliable on
new examples.

The same example also helps explain underfitting. A straight line cannot represent all of the changes
in direction across this sine-wave pattern. However, simply choosing the most complex model is not a
complete solution either. The initial scatter plot provides context for comparing the later curves, but it
cannot establish how well those models generalize. That is why the learning curves and validation
scores in the other sections are important. They provide evidence beyond how closely a fitted line
follows the displayed points.

Reproducibility is another useful part of the setup. Setting the random seed to 0 makes it possible to
generate the same noise again when the code is rerun in the same way. This matters in a group
project because changing the random observations while comparing models could make the
differences harder to interpret. A fixed seed does not make the data better or guarantee good
performance. It helps us keep the starting conditions consistent so we can focus on model
complexity.

The shape of the data also has a practical meaning. X needs 100 rows and one feature column, while
y contains one target value for each observation. Reshaping X changes how the inputs are organized
for the model; it does not create new observations. My takeaway from this role is that setup choices
support the whole experiment. A clear plot, correctly organized arrays, and repeatable data help the
group interpret the later results. A question I would like to explore is whether the conclusions remain
similar when the noise level or random seed changes.


---

## Member 4 – [Full Name]

### My Reflection


---

## Member 5 – [Full Name]

### My Reflection

