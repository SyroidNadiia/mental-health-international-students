# 🏫 SQL Analysis: Impact of Length of Stay on Mental Health of International Students

## 📌 Project Overview
This project analyzes how the **length of stay** affects the **mental health** of international students using **PostgreSQL**. The study is based on data from a Japanese university survey, which suggests that **international students face higher risks of mental health difficulties** compared to the general population. 

Our SQL analysis explores this relationship using key **mental health diagnostic scores** and provides insights into how acculturation and social connectedness impact students' well-being.

---

## 📊 Dataset Description
The dataset includes various demographic and psychological attributes of international students, including:

| Column Name  | Description |
|-------------|-------------|
| `inter_dom` | Whether the student is international (`Inter`) or domestic (`Dom`) |
| `region` | Region of origin (e.g., SEA, EA, SA, Others) |
| `gender` | Gender (Male, Female) |
| `academic` | Academic level (Undergraduate or Graduate) |
| `age` | Age of the student |
| `stay` | Length of stay in years |
| `todep` | Total score of depression (PHQ-9 test) |
| `tosc` | Total score of social connectedness (SCS test) |
| `toas` | Total score of acculturative stress (ASISS test) |

---

## 📌 SQL Query Used
We used **SQL aggregation and filtering** to analyze mental health trends based on students' length of stay.
