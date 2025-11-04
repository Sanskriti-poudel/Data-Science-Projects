In this project, a Linear Regression model was developed to predict housing prices using a structured machine learning pipeline. The dataset contained both numerical and categorical features, with missing values and varying scales.

To ensure efficient preprocessing and modeling, a Pipeline along with a ColumnTransformer was implemented.

Numerical features were handled by imputing missing values using the median strategy, followed by Standard Scaling to normalize the feature distribution.

Categorical features were preprocessed by filling missing values with the most frequent category and then applying One-Hot Encoding to convert them into numerical format.

The ColumnTransformer was used to apply these transformations selectively to the respective feature types within a single unified workflow.

After preprocessing, a Linear Regression model was trained on the transformed dataset to predict housing prices. The model’s performance was evaluated using metrics such as Mean Squared Error (MSE),Root Mean Squared Error(RMSE) and R² Score.

This approach ensured a clean, reproducible, and scalable workflow by automating all preprocessing and modeling steps within a single pipeline, reducing data leakage and improving model reliability.
