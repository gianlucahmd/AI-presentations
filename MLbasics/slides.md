# ML basics
gianluca@ai-academy.com

---

> “Artificial Intelligence, deep learning, machine learning — whatever you’re doing if you don’t understand it — learn it. 

> Because otherwise you’re going to be a dinosaur within 3 years.”

> Mark Cuban

---

## What is Machine Learning?

> "Field of study that gives computers the ability to learn without being explicitly programmed"

1959, Arthur Samuel

---

> "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P if its performance at tasks in T, as measured by P, improves with experience E."

1996, Tom M.Mitchell

---

# In practice: How do we learn?
Teach me how to walk

---

> “Learning means acquiring knowledge and skills and having them readily available from memory so you can make sense of future problems and opportunities.” 

From Make It Stick: The Science of Successful Learning by Peter C. Brown, Henry L. Roediger III, Mark A. McDaniel

---

The big shift in Machine Learning is in how we tell computers to do stuff.

* Past: Here's a function, when new data comes in, apply the function
* ML: Here's some data, and the expected output. Learn the function that given the input gives back the output.

---

In figures - "traditional":
![PC scheme](../images/pc_traditional.png)

---

In figures - ML:
![PC scheme ML](../images/pc_ML.png)

---


In formulas - "traditional":
![Equation traditional](../images/equation_traditional.png)

---

In formulas - ML:
![PC scheme ML](../images/equation_ML.png)

---

What I just described is called
# Supervised Learning

---

Two kinds of supervised learning:
* Regression
* Classification

---

# Regression
* Continuous input, continous output
* Example: stock market

---

# Classification
* Continous input, discrete output
* Example: spam classification, cancer recognition, handwriting recognition, face recognition

---

## Example: price of a house, given its size
![housing price](../images/housingprice.png)

---

## Is it regression or classification?
## It's a regression problem! <!-- .element: class="fragment" -->

---

## Some definitions:
* The value I want to predict (price) is called **label**
* The values I use as input (size) are called **features**

---

## Example: fitting function
![housing price](../images/housingprice_fitting.png)

---

## How do we evaluate our model?
## The "Cost function"
![housing price](../images/housingprice_fitting_errors.png)

---

## Can you tell which one of those models has the lowest cost (which is the best model)?
![housing price](../images/housingprice_overfitting.png)

---

## Can you tell which one of those models has the lowest cost (which is the best model)?
![housing price](../images/housingprice_overfitting_errors.png)

---

## What if new data comes in?
![housing price](../images/housingprice_overfitting_newdata.png)

---

## The problem you just saw is called "overfitting".
![housing price](../images/housingprice_overfitting_labels.png)

---

## Solution: we split the data into a training test and a test set.
The algorithm is evalued based on its performances on data it has never seen, AKA its **generalization ability**.

---

## What if the house price doesn't depend just from its size?
For istance:
* Number of rooms
* Neighborhood
* Year of construction
* Orientation
* Garden y/n?
* Pool

---

## The solution is called "Multi variate regression". 

It's the same exact concept, but in a N-dimensional space. Often the challenge is finding out what are the relevant features that affect a phenomenon (and collect them).

---

## Other example of Multi variage regression:
I want to predict the height of a person. What features do I need?

---

## New example: 




