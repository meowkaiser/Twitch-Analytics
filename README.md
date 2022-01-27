# Twitch-Analytics
## Introduction
I am a data scientist and a Twitch livestreamer and I'll be taking a dive into sponsorships on Twitch livestreams

## Buisness Understanding
Companies who wish to advertise on Twitch also look into sponsoring specific streamers rather than simply use Twitch's advertising system. The idea is to be able to identify streamers who are currently exploding in growth and build a relationship with them early on. Explosive growth is defined as having more gained viewers than years past. If the livestreamer is growing at a slower rate then the years past then that isn't what the company is looking for.

## Data Description
The data was aquired from Twitch's API. The data contained over 5000 of the top livestreamers on Twitch. The data was taken from both 1 year ago and 4 years ago.
The data was organized into train and test sets.

## Modeling
I used a Gradient Boosting Classifier model to create predictions based on the various Twitch statistics. I iterated through Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier

## Model Evaluation
We evaluated our models based on accuracy and recall metrics.
Our model was somewhat prone to false positives however gradient boosting classifier helped minimize this

![image](https://user-images.githubusercontent.com/12703065/151271782-2060d016-ae41-4fa5-b65f-0042ca6a5979.png)
![image](https://user-images.githubusercontent.com/12703065/151271809-dc363fdc-5964-48d8-b01d-0306bc52843b.png)

here I made a prediction on unseen data with a 77% accuracy. Further work would involve exploring different classification models as well as redefining what classifies as "explosive growth"

## Conclusion
If adopted my model will help advertisers quickly identify potential up and coming streamers, be able to start a relationship with them, and be able to put their product in front of their audience relatively cheaply.

## Presentation


```
├── README.md                               <- The top-level README for reviewers of this project
├── Michael Schor Notebook.ipynb            <- The final notebook that uses the target variable based on explosive growth.
├── Mature Audience Prediction.ipynb        <- Started by doing predictions on whether or not the streamer marked their audience as mature
├── Slides.pdf                              <- PDF version of project presentation
```  
