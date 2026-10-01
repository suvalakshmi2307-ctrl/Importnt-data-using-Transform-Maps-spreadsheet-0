# Project Details

## Project Title
Import Data Using Transform Maps in ServiceNow

## Introduction
This project demonstrates the process of importing employee data into ServiceNow using Import Sets and Transform Maps.

## Objective
The objective of this project is to import data from a source file, map the source fields to the ServiceNow target table, transform the data, and verify the imported records.

## Source Data
The employee data contains the following fields:

- Employee ID
- Name
- Department
- Location

## Implementation

### 1. Import Set
An Import Set was created to upload the employee data into ServiceNow.

### 2. Transform Map
A Transform Map was created to connect the imported source data with the target ServiceNow table.

### 3. Field Mapping
The source fields were mapped to the corresponding target fields.

Example:

| Source Field | Target Field |
|---|---|
| Employee ID | Employee ID |
| Name | Name |
| Department | Department |
| Location | Location |

### 4. Data Transformation
The imported data was transformed using the Transform Map.

### 5. Verification
After the transformation was completed, the imported employee records were verified in the ServiceNow table.

## Final Result
The employee data was successfully imported into ServiceNow, and the records were displayed with Employee ID, Name, Department, and Location.

## Skills Demonstrated
- ServiceNow Import Sets
- Transform Maps
- Field Mapping
- Data Import
- Data Validation
