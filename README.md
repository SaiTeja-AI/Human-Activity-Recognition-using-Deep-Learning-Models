# Human-Activity-Recognition-using-Deep-Learning-Models
<p> Human activity recognition, or HAR for short, is a broad field of study concerned with identifying the specific movement or action of a person based on sensor data. The objective of this project is to build a classifier using deep learning models to classify six human
activities like sitting,standing,laying known as static activities and walking,walking upstairs,walking downstairs know as dynamic activities</p>
<h4> About Data </h4>
<p>The dataset was made available and can be downloaded for free from the UCI Machine Learning Repository,
<a href="https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones">Human Activity Recognition Using Smartphones Data Set, UCI Machine Learning Repository</a>.</p>
<p>they have recorded this data from two types of sensors which present in our smart phones,one is accelerometer and other is gyroscope.
 from these two sensors and the data is tri-axial i.e., x,yand z accelerometer(linear acceleration) and gyroscope(angular velocity) from these sensors.Observations were recorded at 50 Hz (i.e. 50 data points per second).Each subject performed the sequence of activities twice, once with the device on their left-hand-side and once with the device on their right-hand side.</p>
 <p>The raw data is not available. Instead, a pre-processed version of the dataset was made available. The pre-processing steps included:</p>
 <ul>
  <li>Pre-processing accelerometer and gyroscope using noise filters.</li>
  <li>Splitting data into fixed windows of 2.56 seconds (128 data points) with 50% overlap</li>
  <li>Splitting of accelerometer data into gravitational (total) and body motion components,i.e,. sensor acceleration signal which has gravitational and body motion components,was seperated by using Butterworth low pass filterinto body acceleration and gravity.</li>
 </ul>
 <h4>Information about features:</h4>
 <p>For each record in dataset is provided:
  <ul>
    <li>Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration</li>
    <li>Triaxial Angular velocity from the gyroscope.</li>
    <li>A 561-feature vector with time and frequency domain variables.</li>
    <li>Its activity label.(WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING).</li>
    <li>An identifier of the subject who carried out the experiment.</li>
  </ul>
  <h4>Some insights into data:</h4>
  <p>
  <ul>
    <li> Number of data points per Activity.</li>
    <img src="img1.png" alt="Number of DataPoints per activity">
    <li>Plotted tBodyAccMag_mean feature find some interesting plot that we can devide activities into stationary and Moving(Dynamic) see below plot</li>
   <img src="img2.png">
    
    
  
 
  
