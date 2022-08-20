# DeepLearning-challenge
  The purpose of this analysis is to create a model to predict if the applicant's venture will be successful. We want to try to optimize the model to get the highest accuracy possible.
  - The target of our model is the IS_SUCCESSFUL column
  - The features of our model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT columns.
  - The EIN and NAME columns should be removed.
  I started with 111 neurons, 3 layers and used 2 diferent activations (relu and sigmoid). I was not able to achieve the goal of 75% and was around 72% accuracy. I tried changing the amount of neurons and layers but still could not reach 75%.
