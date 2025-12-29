# movie recommendation
- Objective: Predict ratings for unwatched movies using machine learning.
- Data: User ratings and movie metadata (titles, genres).



**TRAINING PROCESS**

1- Data preparation
- Merging rating + movie datasets
- Encoding userId and movieId

2-Encoding
- Converting IDs into numerical indexes
- Creating user and movie embeddings

3-Normalization
-Scaling ratings between 0 and 1

4- Model Training
- 10 epochs
- Batch size: 4000
- Optimizer: Adam
- Loss Function: Mean squared Error ( MSE )

5-Loss Curve 
- Training & validation loss decreased.
- Shows improvement in model accuracy

6- Evaluation 
- Tested on validation data
- Ensures predictions generalize well



In summary, this project built a movie recommendation neural network
using Neural Collaborative Filtering. The model uses embeddings and
predicts user preferences as a regression task. Its performance was
evaluated using loss analysis to understand how well the model learns
and generalizes. This project helped improve understanding of neural
recommendation systems and how they differ from traditional
collaborative filtering methods.
