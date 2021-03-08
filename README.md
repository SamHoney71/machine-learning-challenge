<h1> Machine-Learning-Challenge:  Exoplanet Exploration </h1>
<h3> Gary Jeter </h3></br>

<p>Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. </p>
<p> In this challenge, I created two models - a Random Forest Model and a Neural Network Model, and used fine tuning technics to optimize the models. </p>
<p> The Random Forest model was the better predictor of the Kepler telescope planet discovery - Confirmed, False Positive or Candidate. Sixteen variables are used in both models to predict the sighting disposition. </p>
<p> Neither of my models are good enough to predict definitely new exoplanets, but it does help identify which ones to investigate further.  Using data from other telescopes across the globe would help strengthen the models. </p>  

</br>

# Random Forest Model Summary of findings

## Random Forest Model Average Error Degrees with Tuning	
### Micro AVG
<li> precision: 0.79 </li>
<li> recall: 0.68 </li>
<li> f1-score: 0.73 </li>

### Macro AVG 
<li> precision: 0.75 </li>
<li> recall: 0.64 </li>
<li> f1-score: 0.69 </li>


## Top 5 Most Important Features to Predict hidden planets 
 * (0.1454, 'koi_insol'),
 * (0.1180, 'koi_depth'),
 * (0.0830, 'koi_disposition'),
 * (0.0816, 'koi_time0bk'),
 * (0.0792, 'koi_duration'),
 * (0.0680, 'koi_impact'),
 
# Neutral Network Model Summary of findings

* Accuracy: 0.7414
* Loss: 0.6197

