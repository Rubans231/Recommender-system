# Recommender-system
- Building simple recommender projects to revisit and learn my basics
- The dataset is from https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/data
- "simple_recommender" is just as the name suggests, it is simple and thus has many flaws
  - It only accounts for the available data and does not grow according to the user interaction or history.
  - The script I made simply calculates a score based on the vote_average and vote_count available in the dataset (The score is calculated for movies depending on the vote_average mean and also vote_count being above a certain threshold which is calculated using quantile of 90%)
  - <img width="930" height="636" alt="image" src="https://github.com/user-attachments/assets/48d32450-9d1d-4192-be15-db72ec35353c" />
