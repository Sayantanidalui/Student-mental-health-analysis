# 🧠 Student Mental Health Analysis (SQL Project)

## 📌 Overview

This project analyzes mental health patterns in students using only SQL. By examining academic performance, lifestyle habits, and psychological well-being, it uncovers how various factors like sleep, stress, depression, and social time impact student life — all through structured queries and logic-driven insights.


---
## 🛠 Tools & Dataset

- 🧰 *Tools Used:* MySQL Workbench  
- 🗃 *Data Tables:*
  - student_mental_health: Age, gender, CGPA, depression, anxiety, panic attacks, treatment-seeking, marital status, course, year
  - student_lifestyle_dataset: sleep hours, study time, social hours, physical activity, extracurriculars, stress level

---

## ❓ Key Questions Explored

1️⃣ What is the average CGPA based on stress level?  
2️⃣ How many students report depression and anxiety in each course?  
3️⃣ Which students study less than 8 hour and report high stress?  
4️⃣ Who are the top 5 students with lowest sleep but highest CGPA?  
5️⃣ What is the distribution of panic attacks across years of study?  
6️⃣ Which gender reports higher stress levels?  
7️⃣ Create a CTE to find students with both depression and high stress.  
8️⃣ What percentage of overall students report having depression?  
9️⃣ What is the correlation between physical activity and stress?  
🔟 Among married vs unmarried students, who is more likely to seek treatment?  
1️⃣1️⃣ Who spends the most time on social activities?  
1️⃣2️⃣ What is the average social time for students with and without panic attacks?

---

## 📊 Key Insights (One-liners)

1. 📉 Students with high stress have the lowest average CGPA (3.05), while those with low stress average 3.14.  
2. 🧑‍💻 Engineering and BIT students report the highest cases of depression and anxiety.  
3. 🕐 31 students who study <1 hr/day report high stress — a sign of disengagement.  
4. 💤 The top 5 students with the least sleep (avg 5.1 hrs) all had CGPAs between 3.50–4.00.  
5. 🎓 1st-year students report the highest number of panic attacks (43 out of 100).  
6. 👩‍🎓 Female students report higher average stress levels (0.70) than males (0.54).  
7. ⚠ A CTE revealed 17 students out of 100, with both high stress and depression — mostly from engineering and BIT.  
8. 📊 35% of the overall students in the dataset report having depression.  
9. 🏃 Students with high stress get less physical activity (avg 3.51 hrs) than those with low stress (4.47 hrs).  
10. 💍 Married students are more likely to seek specialist help than unmarried ones.  
11. 🗣 Students who spend more time socially are less likely to report panic attacks.  
12. 👥 Students with panic attacks average 2.44 hrs of social time vs 3.04 hrs for those without.

---

## 📖 Storytelling Summary

Mental health is a silent struggle for many students, often hidden behind grades and routines. In this analysis, SQL became a powerful lens to uncover those invisible patterns. I discovered that stress doesn't just affect emotional well-being — it quietly pulls down academic performance. Students with less sleep and minimal social interaction showed warning signs despite their strong grades. Most panic attacks occurred in the early college years, hinting at transition stress. Even subtle habits like low physical activity or short study hours, combined with high stress, raised red flags. With just two tables and no fancy tools — only SQL — we identified real signals pointing to students who need support. This project shows how data, when handled with empathy, can drive meaningful change.

---

## 🧮 SQL Concepts Used

- 🔗 INNER JOIN, WHERE filters
- 📊 GROUP BY, ORDER BY, HAVING
- 🧠 CASE WHEN, COUNT, AVG, ROUND
- 🧱 Common Table Expressions (WITH)
- 📈 Window Functions (RANK(), AVG() OVER)

---

## ✅ Conclusion

This project proves that SQL alone can uncover powerful stories in student mental health data. From academic pressure to emotional red flags, and from lifestyle habits to treatment trends — everything was explored through structured queries. It's not just about code — it's about using data to make student life better, one insight at a time. 

---
