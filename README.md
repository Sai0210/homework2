## Question 7
### Underfitting (max_depth = 1):
The model is too simple (high bias). It performs poorly on both the training and test data because it fails to capture the underlying patterns.

### Good Fit (max_depth = 2):
The model strikes a good balance. It is complex enough to learn the data's structure but not so complex that it memorizes noise. This is evidenced by high accuracy on both training and test sets, with the two values being very close.

### Overfitting (Potential):
If we were to increase the depth further (e.g., max_depth=10), we would likely see the training accuracy reach 100% while the test accuracy would drop. This gap between training and test performance indicates that the model has become too complex (high variance) and has memorized the training data, hurting its ability to generalize.

## Question 8
### Comment on how the boundaries change
### Low k (e.g., k=1):
Boundary: The decision boundary is extremely complex and irregular, forming little "islands" and sharp, jagged edges. It follows the contours of the training data almost perfectly.

### High k (e.g.,k=3 or 5 or 10): 
Boundary: The decision boundary becomes progressively smoother and more generalized. The sharp edges are rounded off, and the small, isolated "islands" of one class inside another disappear.
