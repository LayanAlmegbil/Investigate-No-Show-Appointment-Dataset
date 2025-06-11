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

## Exploratory Analysis
Key visualizations explore:
- No-show rates by factors like scholarship, chronic illness, alcoholism, and SMS.
- Age distribution and attendance correlation.

![](images/sms_impact_chart.png)

## Project Structure
