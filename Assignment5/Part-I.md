## Task 1: Theory Questions

### Question 1: What is the core assumption of Naive Bayes?

**Answer:**
The core assumption of Naive Bayes is is that features and independent given the class label. Which means it treates each feature's contribution to the prediction/decision separately without considering any relation between them.

---

### Question 2: Differentiate between GaussianNB, MultinomialNB, and BernoulliNB

**Answer:**

The three variants of Naive Bayes differ in their assumptions about the distribution of features:

#### **GaussianNB (Gaussian Naive Bayes)** : 
- It is used when features are continuous and create a bell curve (normal distribution).

#### **MultinomialNB (Multinomial Naive Bayes)**
- Used mostly in count based data like providing suggestions based on customer visits count on particular product. 

#### **BernoulliNB (Bernoulli Naive Bayes)**
- Used for bernaulli distribution , i.e. only two classes.

---

### Question 3: Why is Naive Bayes considered suitable for high-dimensional data?

**Answer:**

Naive Bayes is particularly well-suited for high-dimensional data because it's simple, fast, and doesn't try to model relationships between features. Since it assumes feature independence, it avoids the complexity of calculation irrelevant relations, which often slows down  other algorithms in high dimentional spaces.



---

