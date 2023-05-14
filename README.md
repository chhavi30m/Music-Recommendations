# Musicer
Spotify's recommendation system works by using a history of what a specific user likes, and using <b>machine learning</b> to predict the likeability of a new song.<br>
<h4>But what happens when we use deep learning instead of machine learning?</h4>
<br>
I wanted to try experimenting with hidden layers in neural networks. I ended up with this:<br>
<img src='https://github.com/chhavi30m/Musicer/assets/88221999/af320477-8561-45e6-9315-61aaae3117d1'><br>

<h2>Dataset Features</h2>
<b>Danceability</b>: Measure of how likely one is to dance to the sound.<br>
<b>Energy</b>: Measure of the dynamics of energy of the sound <br>
<b>Loudness</b>: Decibel measure of the sound <br>
<b>Acousticness</b>: 0 to 1 measure of whether the track is acoustic<br>
<b>Instrumentalness</b>: Measure of how likely the track is to have no spoken word vocals<br>
<b>Liveness</b>: Reverberation and ambiance measure of the track<br>
<b>Valence</b>: Measure of the musical positiveness conveyed by the track<br>
<b>Tempo</b>: Measure of speed of the track, measured in bpm<br>
<b>Time signature</b>: indicates how many counts are in each measure and which type of note will receive one count<br>

<h2>Correlation Matrix between features </h2>
<img src='https://github.com/chhavi30m/Musicer/assets/88221999/bf6a0385-8e77-4e2d-844c-c54658d42669'>

<h2>Conclusions</h2>
The example provided suggests that a deep learning model was able to successfully differentiate the likeability of music for a user, achieving high training and validation accuracy. <br>This means that the model was able to learn a complex representation of the user's preferences and make accurate predictions about the likeability of songs they had not yet listened to.<br>
While it is worth noting that this model might not generalize well to new users and songs, however in this case, with significant training and validation accuracy (98.57% and 80% respectively), this model successfully differentiates likeability for the user.
