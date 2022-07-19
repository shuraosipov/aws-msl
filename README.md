Resources to prepare for AWS Certified Machine Learning – Specialty (MLS) exam.

## What is Machine Learning?

The following definitions are provided by OpenAI:

1. A field of computer science that gives computers the ability to learn without being explicitly programmed.
2. The scientific study of algorithms and statistical models that computer systems use to effectively perform a specific task without using explicit instructions, relying on patterns and inference instead.
3. A type of artificial intelligence that provides computers with the ability to learn from data, identify patterns and make predictions with little to no human intervention.
4. A branch of artificial intelligence where we try to make machines learn from data themselves without being explicitly programmed by humans.
5. A subfield of computer science and statistics that deals with the design and development of algorithms that can learn from and make predictions on data.


## Resources
* [Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-ml/AWS-Certified-Machine-Learning-Specialty_Exam-Guide.pdf)

# Exam domains



## Domain 3. Modeling

### 3.4 Hyperparameter optimization
**What is a hyperparameter?**

A hyperparameter is a parameter that is used to control the learning process in machine learning. It is a value that is set before the learning process begins and remains constant during the training of the model. A hyperparameter is a parameter that is not directly learned within estimators.

**Hyperparameter tuning**

Hyperparameter tuning can accelerate your productivity by trying many variations of a model, focusing on the most promising combinations of hyperparameter values within the ranges that you specify. However, it's still possible that the tuning job will fail to converge on the best answer, even if the best possible combination of values is within the range that you choose. You should not over-rely on automatic tuning for optimization but rather include it as part of a scientific approach.

[How Hyperparameter Tuning Works](https://docs.aws.amazon.com/sagemaker/latest/dg/automatic-model-tuning-how-it-works.html)

### 3.5 Evaluate machine learning models

**Offline validation strategies:**

- Make use of backtesting with historic data
- Use a K-Fold validation method.

**Reduce the error rates for a model:**

When both training and testing errors are high, it indicates that our model is underfitting the data.
- Try to add more details to the dataset
- Gather more data for training 
- And/or run the training session longer
- Use another algorithm.

[Train faster, more flexible models with Amazon SageMaker Linear Learner](https://aws.amazon.com/blogs/machine-learning/train-faster-more-flexible-models-with-amazon-sagemaker-linear-learner/)

**What metric to measure to minimize the False Negatives?**

The most important metric to evaluate is going to be the recall metric. Since it's extremely important we find all the explicit cases, then this will be our positive class. If the model predicts a video is NOT explicit and the video is explicit, this is the most expensive case. We want to minimize these. This means we want to minimize the False Negatives, which makes Recall the most important metric. 

[Precision and recall](https://en.wikipedia.org/wiki/Precision_and_recall)






