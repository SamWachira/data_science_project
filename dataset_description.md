# Somalia Healthcare Access Dataset

## Description
This document provides a detailed description of the **Somalia Healthcare Access Dataset**, outlining the features included and their significance. The dataset aims to shed light on the various factors influencing healthcare access across the country.

## Dataset Overview
The dataset contains records for individuals from different regions of Somalia. It focuses on demographic details, education levels, healthcare facility access, and perceived barriers to accessing healthcare.

## Features Description

### 1. Region
- **Type:** Categorical (e.g., Awdal, Banaadir, Gedo, etc.)
- **Description:** The administrative region in Somalia where the individual resides.
- **Significance:** Helps in understanding regional disparities in healthcare access and related factors.

### 2. Age
- **Type:** Numerical (Integer)
- **Description:** The age of the individual in years.
- **Significance:** Age can influence health needs, access to services, and health outcomes.

### 3. Gender
- **Type:** Categorical (Male, Female)
- **Description:** The gender of the individual.
- **Significance:** Gender can affect healthcare‑seeking behaviors and access to specific services.

### 4. Income_Level
- **Type:** Categorical (Low, Medium, High)
- **Description:** The self‑reported income level of the individual.
- **Significance:** Economic status is a key determinant of healthcare affordability and access.

### 5. Education_Level
- **Type:** Categorical (None, Primary, Secondary, Higher)
- **Description:** The highest level of education attained by the individual.
- **Significance:** Education often correlates with health literacy, awareness of services, and health‑seeking behaviors.

### 6. Access_to_Facility
- **Type:** Boolean (`True` / `False`)
- **Description:** Indicates whether the individual has access to a healthcare facility.
- **Significance:** A primary indicator of healthcare availability for the individual.

### 7. Distance_to_Facility_km
- **Type:** Numerical (Float) — *present only if `Access_to_Facility` is `True`*
- **Description:** The distance (in kilometers) to the nearest healthcare facility.
- **Significance:** Physical proximity to healthcare services is a crucial factor in access.

### 8. Facility_Type
- **Type:** Categorical (Hospital, Clinic, Health Post) — *present only if `Access_to_Facility` is `True`*
- **Description:** The type of healthcare facility the individual accesses.
- **Significance:** Different facility types offer varying levels of care and services.

### 9. Quality_of_Care
- **Type:** Numerical (Likert scale 1 – 5, where 5 is *excellent*) — *present only if `Access_to_Facility` is `True`*
- **Description:** The individual's perceived quality of care received.
- **Significance:** Reflects the patient’s experience and satisfaction with services provided.

### 10. Health_Insurance
- **Type:** Boolean (`True` / `False`)
- **Description:** Indicates whether the individual has health‑insurance coverage.
- **Significance:** Health insurance can strongly impact the affordability and utilization of healthcare services.

### 11. Common_Health_Issues
- **Type:** Categorical (e.g., Malaria, Diarrhea, Respiratory Infections, Malnutrition, Maternal Health Issues, Injuries, Other)
- **Description:** A list of common health issues reported by the individual.
- **Significance:** Provides insight into prevalent health challenges within the population.

### 12. Satisfaction_with_Healthcare
- **Type:** Numerical (Likert scale 1 – 5, where 5 is *highly satisfied*) — *present only if `Access_to_Facility` is `True`*
- **Description:** The individual’s overall satisfaction with healthcare services.
- **Significance:** Measures overall patient experience and healthcare‑delivery effectiveness.

### 13. Barriers_to_Access
- **Type:** Categorical (e.g., Cost, Distance, Lack of medication, Lack of staff, Lack of awareness, Other)
- **Description:** A list of perceived barriers preventing or hindering access to healthcare services.
- **Significance:** Identifies key challenges that need to be addressed to improve healthcare access.