# UIDAI Aadhaar Data Analysis (Hackathon 2026)

This repository contains a comprehensive exploratory data analysis (EDA) and trend analysis of **UIDAI Aadhaar datasets**, focusing on **Enrolment**, **Biometric Updates**, and **Demographic Updates**. The project is developed as part of **UIDAI Data Hackathon 2026** and aims to extract actionable insights while maintaining strict privacy standards.

## 📊 Datasets Used

All datasets used in this project are **official UIDAI-provided, anonymized, and aggregated API datasets**.

### 1. Aadhaar Enrolment Dataset

**Description:** Captures Aadhaar enrolment activity across Indian states with age-wise distribution.

**Key Columns:**

* `state`
* `date`
* `age_0_5`
* `age_5_17`
* `age_18_greater`

**Analysis Performed:**

* State-wise enrolment distribution
* Age-group demographic analysis
* Monthly and daily enrolment trends
* Anomaly detection in enrolment volume

---

### 2. Aadhaar Biometric Update Dataset

**Description:** Records biometric update activities such as fingerprint, iris, and face updates.

**Key Columns (Representative):**

* `state`
* `date`
* `fingerprint_updates`
* `iris_updates`
* `face_updates`

**Analysis Performed:**

* State-wise biometric workload analysis
* Temporal trends in biometric updates
* Identification of abnormal biometric update spikes

---

### 3. Aadhaar Demographic Update Dataset

**Description:** Contains records of demographic detail updates requested by Aadhaar holders.

**Key Columns (Representative):**

* `state`
* `date`
* `address_updates`
* `name_updates`
* `dob_updates`
* `gender_updates`

**Analysis Performed:**

* Regional demographic update patterns
* Operational load assessment
* Trend analysis of correction requests

---

## ⚙️ Technical Approach

* Data loading and integration using **Pandas**
* Date normalization and feature engineering
* Exploratory Data Analysis (EDA)
* Time-series trend analysis
* Statistical anomaly detection (Mean + 3×Std)
* Visualization using **Matplotlib** and **Seaborn**

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🔐 Privacy & Ethics

* No personal or identifiable information is used
* All data is aggregated and anonymized
* Analysis complies with UIDAI data usage guidelines

---
