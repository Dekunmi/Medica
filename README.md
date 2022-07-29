# Project: Investigate a Dataset - [Medical Appointment No Shows]

## by Rachael Olakunmi Ogunye

## Dataset

> The dataset contains information about 110,527 medical appointments in Brazil with a focus on the reasons why patients miss appointments or fail to attend scheduled appointments without any prior notification or contact with the health service provider. There are 14 features in the main dataset which can be found [here](https://www.kaggle.com/joniarroba/noshowappointments) as well as the feature descriptions.

### Question(s) for Analysis

1: What percentage of patients failed to appear for their appointment?

2: Is there an association between gender and patient no-shows?

3: Is there a relationship between age and patient no-shows?

4: What is the relationship between receiving SMS and patient no-shows?

### Data Wrangling

> The dataset was loaded onto a dataframe and assessed for quality and tidiness issues. There were no missing values in the dataset and datatype conversions was done on the 'Patient ID', 'scheduled_day', 'appointment_day' and 'No_show' columns before carrying out operations on it.


## Summary of Findings

> Majority of the patients showed up for their appointments (80%) while 20% of the patients did not show up for their appointments. Both genders are committed to showing up for their appointments, however, women showed up more for their appointments than men. Patients in the 'old' age class showed up more for their appointments. This shows that the old are more committed.
Majority of the patients did not receive sms. A few patients who did not receive SMS did not show up for their appointment, most patients who received SMS showed up for their appointments, while a few patients received SMS and still did not show up.


### Limitations
Not much inferences can be obtained from the plots as the dataset is mostly categorical in nature.

### References
Kaggle https://www.google.com/url?q=https://www.kaggle.com/joniarroba/noshowappointments&sa=D&source=editors&ust=1653752683050861&usg=AOvVaw3WDOGzy2TH8DlhBpI9s-RM

