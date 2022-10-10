# No-show-appointments

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.<br>
About the dataset:<br>
-PatientId ,<br>
-AppointmentID,<br>
-Gender of the patient,<br>
-ScheduledDay: which tells us on what day the patient set up for their appointment,<br>
-Appointment Day <br>
-Age, <br>
-Neighborhood:which indicates the location of the hospital,<br>
-Scholarship: indicates whether or not the patient is enrolled in Brasilian welfare program which provided financial aid to poor Brazilian families.<br>
And to describe the situation of the patient it gives information on whether or not the patient is diagnosed by: <br>
-Hipertension <br>
-Diabetes, <br>
-Alcoholism <br>
-Handcap; <br>
-SMS_received: Whether or not the patient received an SMS.<br>
-No-show: which indicates either if the patient show up or not for their appointment.<br>

>The dataset can be found [here](https://www.kaggle.com/datasets/joniarroba/noshowappointments) <br>

## Summary of Findings

At the end of the analysis, we conclude that in order to predict if a patient will show up for their scheduled appointment or not, we have to take into account 
those factors: <br>

1- Whether or not the patient has been diagnosed or not, and the type of it. (The hypertension category took the higher percentage)<br>
2- The gender of the patient.<br>
3- The time and the day picked.<br>
4- The neighbourhood. <br>
