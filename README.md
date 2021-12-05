The dataset are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

Note:
1. Implemented Logistic regression to predict the wine quality (rating >= 6.5, which is 'Good', otherwise 'Bad')
2. Imbalanced the dateset, I Implemented SMOTE to deal with the issue.
3. Hyperparameter tuning 'C'- regularization term.
