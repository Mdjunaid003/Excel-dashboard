
# Student Course Engagement Data

Dashboard:
![Image](https://github.com/user-attachments/assets/3da60798-634c-47e2-a68a-e0b6ff1abfcd)

## 1.Data Overview
This project analyzes and visualizes student engagement by leveraging data related to student demographics, enrollment patterns, and attendance records. The dataset comprises key attributes, including:
*	Student_ID – Unique identifier for each student.
*	Name – Student name 
*	Age – Age of the student.
*	Gender – Gender of the student (Male, Female, Rather not say).
*	Course_Name – The course the student is enrolled in (e.g., Data Analyst, AI, WD, ML, JAVA).
*	Enrollment_Date – The date the student enrolled in the course.
*	Attendance_Percentage – Percentage of classes attended by the student.
The primary objective is to derive data-driven insights by calculating critical metrics such as:
*	Course_Completion_Status – Whether the student has completed the course (Complete/Incomplete).
*	Satisfaction_Score – A score given by students based on their satisfaction with the course (ranging from 1 to 10).
*	Retention_Status – Whether the student is retained for further courses (Yes, No, N/A).
Through advanced data analysis and visualization techniques, this project aims to provide actionable insights that support informed decision-making to enhance student engagement and academic success.

## 2. Data Cleaning
![Image](https://github.com/user-attachments/assets/fc36bf65-bce2-476f-8e30-b11912d0e41e)
* removed duplication (10500) ==> 10k raw data
* Name column have been trimmed and standardised 
* Missing values in age column have been filled with average age of   23
* Missing values in gender column has been replaced with 'Rather not say'
* Course names has been filtered and standardised 
* Missing values in percentage column has converted to average i.e. 75
* Missing values in satisfaction column changed to average '5'
* Missing values in Retention column changed with 'N/A'

## 3. EDA - Exploratory data analysisKey Insights
1️. Course Satisfaction Trends

* Courses like ML and Java may have more students or higher satisfaction rates.
* Data Analytics might need improvements in course content, teaching methods, or engagement strategies.
* The satisfaction scores are relatively close, meaning all courses have a good level of engagement.
![Image](https://github.com/user-attachments/assets/c2719adc-6eb0-480d-89ee-c3f520b632b2)

2️.Attendance Trends

* ML and Java have the highest attendance counts, suggesting high student participation in these courses.
* Data Analytics shows the lowest attendance count, meaning it might need improvements in course structure or engagement strategies.
* Web Dev has lower attendance compared to ML and Java but is still higher than Data Analytics.
![Image](https://github.com/user-attachments/assets/04e636f7-1e64-49f0-9427-87bc0759da0f)

3.Gender Distribution

* The distribution of students is almost equal between Male and Female (45% each), indicating a balanced gender representation in the dataset.
* 10% of students preferred not to disclose their gender, which might indicate privacy concerns or inclusivity in the dataset.
![Image](https://github.com/user-attachments/assets/6bea3d0c-f620-4300-9b1b-24f314521307)

4.Total Student Count & Age Statistics

* Total number of students: 10,000.
* Average student age: 23 years.
* The average age of students shows are youngsters, probably they are the recent graduates.
![Image](https://github.com/user-attachments/assets/71d31fc8-4c5d-45e3-a335-9b6e0456f480)
![Image](https://github.com/user-attachments/assets/778cbdb3-afb4-4527-8b48-bcbf48c32334)

5.Retention Trends

* Overall high participation across courses, with most students falling under the "Yes" category.
*  Java leads in participation, followed by ML and AI.
*  Courses with high "No" and "N/A" counts (Data Analytics, Web Dev) may need more engagement strategies to improve completion rates.
![Image](https://github.com/user-attachments/assets/b0dd6fb9-37cc-4d63-a1f8-9cbbe2cc9969)

6.Enrollment Trends

* The enrollment count fluctuates significantly across months, rather than following a steady increase or decrease.
* Enrollment drops after January but recovers in March-May.
* A decline in June is observed, followed by a rise in July-August.
* Enrollment remains steady from September to October, then dips in November before slightly rising in December.
![Image](https://github.com/user-attachments/assets/3681a3cc-f5ad-45fc-acd0-3c36b0fed899)

## 4.Insights and Report

* The satisfaction scores are relatively close, meaning all courses have a good level of engagement.
* Data Analytics might need improvements in course content, teaching methods, or engagement strategies.
* ML and Java have the highest attendance counts, suggesting high student participation in these courses. 
* Balanced Gender Participation: The dataset does not show a gender disparity, suggesting equal interest in the courses among male and female students.
* Overall high participation across courses, with most students falling under the "Yes" category.
* Fluctuating Enrollment Pattern: The enrollment count fluctuates significantly across months, rather than following a steady increase or decrease.
* Retention Challenges: A notable drop-off in student engagement over time indicates potential challenges in curriculum engagement.

## Overall Conclusion for the Student Course Engagement Analysis Project

The Student Engagement Dashboard provides valuable insights into student participation, retention, and satisfaction across different courses. The analysis highlights key trends in enrollment, retention, attendance, and feedback to assess student engagement effectively.

## Key Takeaways:

* The satisfaction scores are relatively close, meaning all courses have a good level of engagement.
* Web Dev’s attendance is declining; consider adding interactive elements to retain engagement.
* Since both male and female participation is equal, efforts can focus on maintaining this balance and ensuring equal opportunities for all students.
*  Gender disparities (if any) in "No" and "N/A" categories should be further analyzed to ensure inclusivity.
* Promoting intensive boot camps or specialized workshops can help sustain interest of students for enrollment.
* Data Analytics might need improvements in course content, teaching methods, or engagement strategies.

## Final Recommendations:

* Increse in Enrollment - Focus on providing demo classes and discounts in course fees may help to increse enrollment.
* Improve Retention Strategies – Personalized mentoring and better course structures can reduce drop-off rates.
* Latest skills - Providing latest skills according to firm trends will not only help in enrollment but also in retention rates.
* Enhance Digital Marketing & Outreach – Promoting high-engagement courses while refining struggling ones can help maintain a strong student base.

