
**Team**

***

Narsimha Narayankhedkar (narayankhedkarn19@students.ecu.edu)  
Denise Bruce(brucea02@students.ecu.edu)  
Connor Bullard(bullardc21@students.ecu.edu)  

**Group Homework 2**

***

Anomaly Event Detection  

**Quick Start**

***

Clone the repository, open ipynb file in Jupyter Notebook and run the code.

**Prerequisites**: 

***

All the below libraries are required to run this code.
*pandas*  
*numpy*  
*PrettyTable*  
*matplotlib*  


**Scatter Plot of the Anomaly events**

***


![ ](/HW2/Pictures/Anomaly_events.png  "Anomaly Events")

**Find an appropriate window size and initial threshold.**

***
The below table was generated by the sliding window threshold method after iterating for different window size & Initial Threshold values.

As you can see from the highlighted rows, we have selected the below rows for having the best Anomaly Event Accuracy rate & Normal Event Accuracy rates.  

When **q = 80 & d = 400**, Anomaly Accuracy is 80.52 % & Normal Accuracy is 81.76%.  


![ ](/HW2/Pictures/Accuracy_table.png  "Accuracy table")

**Scatter Plot of Actual vs Calculated Anomaly Events .**

***
![ ](/HW2/Pictures/Anomaly_Detection.png  "Anomaly Detection")




