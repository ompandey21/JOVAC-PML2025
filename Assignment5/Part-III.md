## Task 7: Conceptual Questions

### Question 1:  What is the difference between Bagging and Boosting?

**Answer:**
- Bagging builds many models independently and combines them to reduce variance (e.g., Random Forest).
- Boosting builds models one after another, each one learning from the previous model’s mistakes — it focuses on reducing bias.

---

### Question 2: How does Random Forest reduce variance?

**Answer:**

- It creates many decision trees on random subsets of data and features, and averages their results.
- This “voting” smooths out individual errors and prevents overfitting from any single tree.

---

### Question 3: What is the weakness of boosting-based methods?

**Answer:**

- Boosting can overfit noisy data or outliers because it tries too hard to fix every mistake.
- It’s also more sensitive to overfitting and usually slower to train than bagging methods.


---

