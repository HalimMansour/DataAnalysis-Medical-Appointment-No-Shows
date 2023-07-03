# Medical Appointments Dataset

This dataset collects information from 100k medical appointments and focuses on the question of whether or not patients show up for their appointments. It includes several characteristics about the patients in each row.

## Dataset Information

- `PatientId`: Unique identifier for each patient.
- `AppointmentID`: Unique identifier for each appointment.
- `Gender`: Gender of the patient.
- `ScheduledDay`: The day the patient set up their appointment.
- `AppointmentDay`: The day of the actual appointment.
- `Age`: Age of the patient.
- `Neighbourhood`: The location of the hospital.
- `Scholarship`: Indicates whether the patient is enrolled in the Brazilian welfare program Bolsa Família.
- `Hipertension`: Indicates whether the patient has hypertension (1 for True, 0 for False).
- `Diabetes`: Indicates whether the patient has diabetes (1 for True, 0 for False).
- `Alcoholism`: Indicates whether the patient has alcoholism (1 for True, 0 for False).
- `Handcap`: Indicates the level of handicap the patient has (0 for no handicap, 1-4 indicating different levels of handicap).
- `SMS_received`: Indicates whether the patient received an SMS reminder for the appointment (1 for True, 0 for False).
- `No-show`: Indicates whether the patient showed up to their appointment (`No`) or did not show up (`Yes`).

## Goal

The goal of this dataset is to analyze the factors that are important in predicting if a patient will show up for their scheduled appointment. By understanding these factors, we can potentially improve appointment attendance rates and optimize medical resources.

## Contents

This repository contains the following files:

- `medical_appointments.csv`: The dataset file in CSV format.
- `medical_appointments.ipynb`: Jupyter Notebook containing the Python code for data wrangling, cleaning, and exploration of the dataset.
- `README.md`: This file providing information about the dataset and repository.

## Data Wrangling, Cleaning, and Exploration

The Jupyter Notebook `medical_appointments.ipynb` in this repository provides the Python code for performing data wrangling, cleaning, and exploration of the dataset. It includes steps to clean the data, handle missing values, perform data transformations, and conduct exploratory analysis to gain insights into the dataset.

## Acknowledgements

The dataset used in this project is publicly available on [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments). The data was originally collected and made available by Joni Hoppen and Aquarela Advanced Analytics.
