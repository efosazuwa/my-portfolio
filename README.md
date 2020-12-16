# My Portfolio
A Sampling of Data Science projects that I have completed or I'm working on.

# [Project 1: Electric Vehicle Charging Detection(Unfinished)](https://colab.research.google.com/drive/1imM6GxT0zFiLUi0VVbpDA_JsNNKIwn16#scrollTo=O6a21YEWCzbF)
* Build visualizations that identify annomalies with seaborn and plotly
* Engineered features from primary dataset 
* Investigate annomaly detection with naive gaussian methods, Isolation forrests, and Local Outlier Factor. 
* TODO build different forecasting models with ARMA FFT, and RNN
* TODO Build a client facing API using flask 

![](/images/EV_charging_annomalies.png)

# [Project 2: Ball Image Classifier](https://github.com/PlayingNumbers/ball_image_classifier)
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 

![](/images/matrix_results.png)
