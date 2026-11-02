# Group 4 – Module 08 Lab Contributions
**Course:** ITAI 1371 – Introduction to Machine Learning  
**Lab:** Module 08 – Bias-Variance Tradeoff and Overfitting  
**Group:** Group 4  

---

## Member 1 – Patrick Rostand Gandjouon Tchassem

### My Contribution

For this lab, I worked on preparing the Google Colab notebook and reviewing the code for the bias-variance tradeoff exercises. I worked with the polynomial regression models using degrees 1, 4, and 15 and checked the graphs to understand how model complexity affects the results.

I also reviewed the learning curves for the underfitting and overfitting models. One thing I paid attention to was the difference between the training and cross-validation scores. The degree 15 model had some very low validation scores, so I spent time trying to understand what those results meant.

I helped organize the notebook and review the knowledge-check answers to make sure they matched the graphs. I also worked on preparing the GitHub reflection and contribution files so every group member would have a place to explain their work.

My main focus was understanding the results, checking the notebook, and helping organize the group's documentation.

---

## Member 2 – saimi manasiya
My contribution to Lab 08 was reviewing the concepts of the bias-variance tradeoff and understanding the results of the polynomial regression models. I examined how models with different polynomial degrees behave and how their learning curves help identify underfitting and overfitting. I also reviewed the knowledge-check questions and the explanations about training scores, cross-validation scores, and model generalization. Through this activity, I contributed to understanding the notebook results and connecting the practical observations with the concepts learned in class.



---

## Member 3 – Kenneth Kouokam

My assigned contribution to Module 08 is Synthetic Data and Initial Exploration. This role covers the
setup that creates 100 input values between -5 and 5 and generates the target values by adding
random noise to a sine function. The setup uses NumPy with random seed 0 so the same
observations can be reproduced. My part includes checking that X has 100 rows and one feature,
that y contains 100 corresponding values, and that the initial scatter plot displays the data clearly.

The explanation for my section focuses on the difference between the underlying sine-wave pattern
and the random variation around it. The noise helps show why a model should not try to follow every
observation exactly. I also explain why all group members need to use the same generated data
when comparing polynomial models of degrees 1, 4, and 15. This gives the group a consistent
starting point and helps connect the initial data exploration to the later discussion of underfitting,
overfitting, and performance on new examples.


---

## Member 4 – Anavictoria Cavazos

My personal contribution to this lab mainly focuses on the degree 15 that is seen in task 2.
When examining the training/validation gap and score variation what is noticed is how the huge gap between the red line and the 
green line display the main issue of the use of degree 15. What appears to be happening is that the training score shows how the model
can easily remember tested data, but the green line (the cross validation) shows how it has a limit of being able to predict new data. 
That is why that huge gap displayed by the green line shows that the model has trouble or problems with the new data when there are only
a few samples presented, but as more and more data gets inserted it allows the cross validation to become better because the line does not
have much wiggle room to go all over the place, instead it is restricted to stay confined with less room for error. 
To summarize what this shows when comapring to degree 1 is how you want to find the right degree that does not show underfitting or 
overfitting. In degree 1 both lines stay too close to the bottom meaning the model is too simple, while the gap from both lines in degree
15 show that it is too complex, so in a model you want something in between those two when it comes to complexity, you want a balance.


---

## Member 5 – Hashim Sayed Hoosini

Due to my demanding work schedule, I primarily had to work independently on this lab to keep pace with the coursework. I dedicated my individual study time to running the notebook code, verifying the outputs, and deeply analyzing the core concepts of underfitting (high bias), overfitting (high variance), and how the bias-variance tradeoff determines a model's generalizability. This independent execution allowed me to thoroughly digest the behavior of the polynomial regression curves and build a solid foundation before coordinating back with my group.

Following our group's coordination, my assigned contribution was to focus specifically on the diagnostics of learning curves and the mechanics of high bias. I investigated how simple models like the Degree 1 polynomial fail to improve even when provided with more training examples, and I successfully documented these observations in the lab notebook. Throughout this process, I maintained communication with my team members, shared my findings, followed our agreed-upon instructions, and verified that my individual work aligned perfectly with the rest of the group's collective tasks.

