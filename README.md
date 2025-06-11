# 📅 No-show Medical Appointments Analysis

This project is part of the Data Analyst Nanodegree from Udacity that explores a dataset of over 100,000 medical appointments in Brazil to uncover what factors influence whether patients attend their appointments.

## Research Questions
- What factors are associated with higher no-show rates?
- Does receiving an SMS reduce the probability of missing an appointment?
- Are older patients more likely to show up?

## Dataset
The dataset was obtained from [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments).

It includes:
- Appointment dates
- Patient demographics
- Medical conditions
- SMS reminders
- Final no-show status

> **Note**: Due to file size restrictions, you may need to manually download the dataset and place it in the `/data` folder.

## Data Cleaning
- Standardized column names
- Converted date fields
- Created binary target `no_show_binary` (1 = missed, 0 = attended)
- Removed duplicates

## Key Visualizations

Below are some insights from the data visualizations:

### 1. No-show Rate by Different Factors

These bar charts show how different patient attributes affect the rate of missed appointments.

| Scholarship | Hypertension | Diabetes |
|-------------|--------------|----------|
| ![](images/no-show-scholarship.png) | ![](images/no-show-hipertention.png) | ![](images/no-show-diabetes.png) |

| Alcoholism | SMS Received | SMS Impact |
|------------|---------------|-------------|
| ![](images/no-show-alcoholism.png) | ![](images/no-show-sms.png) | ![](images/no-show-impact-of-sms.png) |

### 2. Age Distribution by Show/No-show

This chart shows that older patients tend to attend appointments more reliably than younger ones.

<img src="images/no-show-age-distribution.png" width="400"/>
