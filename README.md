<h1> Machine-Learning-Challenge:  Exoplanet Exploration </h1>
<h3> Gary Jeter </h3></br>

<p>Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.</p>
<p> In this challenge, I created two models - a Random Forest Model and a Neural Network Model, and used fine tuning technics to optimize the models</p>
<p> The Random Forest model was the better predictor of the Kepler telescope planet discovery - Confirmed, False Positive or Candidate. Sixteen variables are used in both models to predict the sighting disposition. </p>

</br>

<h3> Random Forest Model Summary of findings </h3>

                precision    recall  f1-score   support

     CANDIDATE       0.59      0.51      0.55       411
     CONFIRMED       0.78      0.81      0.79       484
FALSE POSITIVE       0.80      0.84      0.82       853

      accuracy                           0.75      1748
     macro avg       0.72      0.72      0.72      1748
  weighted avg       0.75      0.75      0.75      1748

<h3> Neural Network Model Summary of Findings </h3>

1748/1748 - 0s - loss: 0.6009 - accuracy: 0.7489
Loss: 0.6009191288282452, Accuracy: 0.7488558292388916

