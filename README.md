# HHC_Software_Data

The data file contains data developed to solve the Home Health Care Routing (HHC) problem.

These data are real data from the city of Isparta in Türkiye. The data is randomly generated.

Explanation information for the data is below:
patientID: ID value of the patients. 0 always belongs to the home health care center.
location: Latitude and longitude information of the patient location
lat: Latitude information of the patient address.
lon: Longitude information of the patient address.
priority: A decimal number indicating the priority of care for patients. It is a value defined by the health center according to the patient's health conditions.
tw1: Time window1. The earliest time period the patient requests for care.
tw2: Time window2. The latest time period the patient requests for care.
careDuration: The time required for health care at the patient's address. This value is predefined by the health center.
active: 1 if the patient will be visited, 0 otherwise. A value of 0 is entered for patients for whom a health care plan will not be made.
skill: The level of health care needed by the patient.
explanation: Explanation line.


