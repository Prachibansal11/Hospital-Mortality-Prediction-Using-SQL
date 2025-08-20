# 🏥 Hospital Mortality Analysis Dashboard

![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/e7d1e0072ae3ea8a6814d481058771e2360f5129/Hospital%20Mortality%20Dashboard%20(Tableau).png)

# 🏥 Hospital Mortality Analysis Dashboard

A data analysis project aimed at uncovering patterns and insights related to in-hospital mortality using **SQL**, **Excel**, and **Tableau**.

---

## 📌 Business Problem

Healthcare professionals are trying to identify the **main causes of in-hospital mortality** for admitted patients.  
By understanding these causes early, professionals can develop **targeted interventions** and implement **evidence-based protocols** to reduce preventable deaths.

---

## 🛠️ Tools Used

- 📊 **Excel** – Data import, initial cleaning
- 🗄️ **MySQL** – Data querying and analysis
- 📈 **Tableau** – Interactive dashboard creation

---

## 📂 Dataset

The dataset used in this analysis was sourced from public health data repositories and imported into **Excel** for initial cleaning before being transferred to **MySQL** for deeper analysis.

---

## 🚀 My Approach to Solving the Problem

1. **Data Cleaning & Preparation**
   - Cleaned the raw dataset in Excel.
   - Uploaded and structured the data in MySQL.
  
2. **SQL Analysis**
   - Conducted queries to analyze attributes such as:
     - Age
     - Ethnicity
     - Gender
     - Weight & BMI
     - Heart Rate
     - ICU Admit Source & Type
     - Comorbidities
     - ICU Length of Stay

3. **Insights Extraction**
   - Identified patterns and trends from the SQL outputs.
  
4. **Dashboard Design**
   - Created an **interactive Tableau dashboard** to visualize findings in a meaningful, user-friendly manner.

---


## 📊 Insights I Gathered
 Below I will show the results of the SQL queries I conducted and provide explanations of the patterns and trends I found throughout the analysis.

1. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/a9c57d60cacc29e43caa9ca0063ea065cc589bc2/1h.png)
- Out of the 10,000 admitted patients in the hospital, a total of 634 patients died, which translates to 6.34%. This meant that understanding the factors contributing to in-hospital mortality was highly important in improving patient care and reducing preventable deaths.

2. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/b866eab26bbc1a753d834d6a53d5835c098fdfda/2h.png)
- This output showed the amount of patients that died and survived in each age group, categorized by 10-year intervals. There were far more admitted patients between the ages of 50-89 compared to patients who were between 0-49. Observing the results more, we can see that patients between ages 0-9 had the highest death percentage and each 10-year age group in the 50-89 range had a slight increase in death percentage. Nearly 1 in every 6 patients between the ages of 70-89 died in the hospital.

3. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/e3d30c44422dd693b8c02dbe4388533a5681d04c/3h.png)
- This output further proves that the death probability of a patient in the hospital rises as they get older.


4a. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/57d2ab999dacd03c320c715a3de857585ad25c67/4h1.png)


4b. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/c53b5117c6ac14b8ed13588ab5135583be87b37c/4h2.png)
- These two outputs give more insight to the outcomes of patients in each ICU admit source & type. A vast majority of the patients were admitted to the "Accident & Emergency" ICU admit source and it also experienced the highest number of deaths. However, the ICU admit source with the highest probability of death was "Floor" with a percentage of 11.76. "Other ICU" was ignored because of its very small sample size.
- In the second output where death results are shown for each ICU type, there is a clear outlier: Med-Surg ICU

5. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/ffa77106da411382b5bf678996d603df78784d63/5h.png)
- Average weight, BMI, and max heart rate among the patients that died.

- The average weight of 67.57 kg (149 in lbs) suggests that, on average, the patients who passed away had a relatively moderate weight. The average BMI of 23.3 indicates that, on average, the patients who died had a BMI within the normal range. This suggests that weight alone may not be the sole determinant of mortality, as individuals with a normal BMI can also face significant health risks and complications leading to hospital death. The average maximum heart rate of 115.1 highlights a potential cardiovascular aspect in the patients' health profiles. Elevated heart rates can be indicative of underlying conditions (source), such as cardiac distress or organ failure, which might have contributed to the hospital mortality outcomes observed.

6. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/ecbcbab5b4c06e7e5c244c156b5c6d6c8fe3fbee/6h.png)
- There were a total of 8 comorbidities in the dataset, and the 3 shown in the output results above (Diabetes, Immunosuppression, and Solid Tumor) had the highest probability of death with diabetes being the highest, by far. This highlights the importance of managing and monitoring this condition effectively during hospitalization.

7. ![Banner](https://raw.githubusercontent.com/Prachibansal11/Hospital-Mortality-Prediction-Using-SQL/077b902a42641667b70fa2ecaf9a137fe8a00d49/7h.png)
- Generally speaking, and as shown by this output, prolonged stays in the ICU are associated with higher mortality rates (source). An increased length of stay in the ICU can be due to a number of reasons, such as cardiovascular system diseases, nervous system diseases, infections, underlying illnesses, and increased exposure to potential complications (source). According to this output, a patient who stayed in the ICU for longer than a day had a higher chance of death compared to someone who spent less than a day in the ICU.

## 🧠 Conclusion

- **Age** is a strong predictor of mortality; nearly 20% of patients aged 70+ died in hospital.
- **Comorbidities** like diabetes significantly raise mortality risks.
- **Heart rate** is a key physiological marker for assessing patient condition.
- **ICU duration** is directly associated with risk; prolonged stays lead to higher mortality.

---

## 🔎 Recommendations

- Future datasets should include:
  - **Treatment details** (medications, procedures)
  - **Vital signs** beyond heart rate
  - **Socioeconomic indicators**
  - **Psychosocial factors** (mental health, support systems)

Incorporating these factors will allow for a **more holistic** understanding of patient mortality and lead to **better predictive models** and **clinical decisions**.

---
## ⭐ Feedback

If you found this project helpful or insightful, please consider **starring** ⭐ the repository to show your support and encourage future contributions!


---

