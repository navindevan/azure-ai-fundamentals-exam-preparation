In my previous article we explored [Understanding Machine Learning and Machine Learning Model](https://github.com/navindevan/azure-ai-fundamentals-exam-preparation/blob/main/ai-fundamental-principles-machine-learning/understanding-ml-ml-models.md). In this article we are going to explore the Common Types of  Machine Learning.

### Overview
The common types of machine learning are fundamental for both beginners and seasoned professionals alike. We explore the core concepts of regression, classification, clustering, deep learning, and essential elements of machine learning, such as features, labels, and confusion matrices.

![machine-learning-types.png](https://github.com/navindevan/azure-ai-fundamentals-exam-preparation/blob/main/resources/img/machine-learning-types.png)

Image Credit: learn.microsoft.com

### Regression. Predicting Continuous Values
Regression analysis is a type of supervised learning used to predict continuous outcomes. In essence, it analyzes the relationship between one dependent variable and one or more independent variables. The goal is to understand how the dependent variable changes when the independent variables are varied.

**Example:** Consider a real estate scenario where we want to predict house prices based on features like area, number of bedrooms, and location. By collecting data on past house sales, we can train a regression model to predict the price of a new house based on its features.

### Classification. Categorizing Data
Classification is another form of supervised learning where the goal is to categorize data points into predefined classes or categories. It's widely used in various applications such as spam detection, sentiment analysis, and medical diagnosis.

**The two common classification scenarios are:**
  +  Binary Classification
  +  Multiclass Classification

### Binary Classification
In binary classification, the label determines whether the observed item belongs to a particular class or not. Alternatively stated, returns true or false.

**Example:** Imagine a scenario where we want to classify emails as either spam or not spam. We can use features like the presence of specific keywords, sender information, and email format to train a classification   model. Once trained, the model can accurately classify new emails as spam or not spam.

### Multiclass Classification
Multiclass classification broadens the scope of binary classification by forecasting a label that signifies one among several potential classes.

**Example:** Determining the breed of a dog (Labrador Retriever, German Shepherd, or Golden Retriever) based on its size and fur characteristics.

### Clustering. Uncovering Hidden Patterns
Unlike regression and classification, clustering is an unsupervised learning technique where the goal is to group similar data points together based on their intrinsic characteristics. It's particularly useful for exploratory data analysis and identifying hidden patterns within datasets.

**Example:** Consider a customer segmentation task for a retail business. By clustering customers based on their purchasing behavior, demographics, and shopping preferences, the business can tailor marketing strategies to different customer segments, thereby maximizing sales and customer satisfaction.

### Conclusion
Understanding the core concepts and types of machine learning is essential for building robust and effective predictive models in real-world applications. As technology continues to advance, the possibilities for leveraging machine learning to solve complex problems are virtually limitless.
