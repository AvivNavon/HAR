# Topics In Data Science - Final Project \n| Human Activity Recognition\n

Human activity recognition has wide applications in healthcare, smart environments (like IoT), and many more.

The main goal of the following work is to build an activity recognition classifier, using acceleration data generated by a user?s cell phone. 

The Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living while carrying a waist-mounted smartphone with embedded inertial sensors.<sup>[1](#myfootnote1)</sup>

We will try to use different predictive algorithms, and test the models accuracy on an independent test set. 

## Description of Experiment

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities:

  - walking 
  - walking upstairs
  - walking downstairs
  - sitting
  - standing
  - laying 
  
The activities where performed while wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually.^[Follow 
[this link](https://www.youtube.com/watch?v=XOEN9W05_4A&feature=youtu.be) 
or simply click on the above image to see a video of the 6 activities recorded in the experiment with one of the participants.]

[![link to video](http://img.youtube.com/vi/XOEN9W05_4A/0.jpg "Experiment Image")](https://www.youtube.com/watch?v=XOEN9W05_4A)

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

The obtained data set, which consists of 562 features (explanatory variables) and the response, has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.


<a name="myfootnote1">1</a>: The data is available at the UC Irvine Machine Learning Repository [(link to data)](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) 
