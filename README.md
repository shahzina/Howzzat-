# Howzzat!


 ![cricket](https://media.gettyimages.com/vectors/cricket-batsman-vector-id483913507?s=612x612)

### All about the endeavour

### Goal : 
Train a model to predict the winner of a cricket match given the two teams playing, where they are playing and in what month they are playing. 

To feed a model cricket data for the last 20 years including cricket matches of all three formats, i.e., One Day International, T20 and Test cricket. The model should be able to predict the winner of the match based on the input features which are the two teams playing, time of year(month), the ground they're playing on etc. 
Data has been scraped from the ESPN website and is heavily categorical. Cleaning the data mostly involved checking for null values and encoding the data to make it fit to feed to the model. 

The models trained were a Random Forest Classifier, Deep Neural Net and a Linear Regression. 

![nn performance](https://github.com/shahzina/Howzzat_Project/blob/master/Neural%20Net%20Performance.png)⁩


### Progress-
Succesfully trained two models, however, accuracy is low as the occurrences of two teams playing each other in a particular format is less, therefore, the model needs to be trained on more data to get better results.

### Next Steps -
1- Save the encodings and reuse them in a Flask App, then deploy it on Heroku enabling user input. 
2- Get data dating back to 50 years and retrain models. 
3- Get data with the team distribution to achieve more accuracy, example, the number of batsmen, bowlers and all-rounders in the team, and the age distribution of players. 
4- Compare the results and study possible causes of increase or decrease in accuracy. 
