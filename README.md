
**Anomaly Event Detection**  
***
Anomaly detection is one of the most interesting topic in data science. There are many approaches for solving that problem starting on simple global thresholds ending on advanced machine learning. 

I will be implementing a sliding window algorithm on the Nitrates data for Anomaly Event Detection.



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


![ ](/Pictures/Anomaly_events.png  "Anomaly Events")

**Find an appropriate window size and initial threshold.**

***
The below table was generated by the sliding window threshold method after iterating for different window size & Initial Threshold values.

As you can see from the highlighted rows, we have selected the below rows for having the best Anomaly Event Accuracy rate & Normal Event Accuracy rates.  

When **Percentile(q) = 80 & Window Size(d) = 400**, Anomaly Accuracy is 80.52 % & Normal Accuracy is 81.76%.  


![ ](/Pictures/Accuracy_table.png  "Accuracy table")

**Scatter Plot of Actual vs Calculated Anomaly Events .**

***
![ ](/Pictures/Anomaly_Detection.png  "Anomaly Detection")




