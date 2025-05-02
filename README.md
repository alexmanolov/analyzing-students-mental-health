Analyzing Students' Mental Health

DataCamp Portfolio Project | SQL (PostgreSQL)


Project Overview
This project explores the mental health of students at an international university in Japan. The university conducted a survey in 2018, aiming to understand how studying abroad impacts students' mental well-being. The research, ethically approved and published in 2019, found that:
    - International students are at higher risk of mental health difficulties than the general population.
    - Social connectedness (belonging to a group) and acculturative stress (stress from adapting to a new culture) are predictive of depression.

Using PostgreSQL, I replicated and extended the analysis to investigate whether these findings are supported by the data - and whether length of stay plays a role in students' mental health.


Key Questions
    - Do international students show higher stress and depression levels than local students?
    - Does a longer stay in the host country correlate with improved mental health?
    - How does social support affect students' well-being?


Data and Tools
Language: SQL (PostgreSQL)
Environment: DataCamp Notebook Workspace
Dataset: Survey of university students (2018), anonymised and preloaded in DataCamp


Selected Columns in the Dataset:
student_id: Unique identifier for each student
gender: Male/Female/Other
age: Age in years
nationality: Country of origin
length_of_stay: Duration in months
depression_score: Numeric scale
stress_score: Numeric scale
social_support_score: Numeric scale
is_international: Boolean (1 = international, 0 = domestic)


Summary of Findings
    - International students displayed consistently higher levels of depression and stress.
    - Longer length of stay correlated with reduced acculturative stress, indicating gradual adaptation.
    - Students with higher social support scores showed notably lower depression scores.

These results reinforce the original study's conclusions, illustrating the complex interplay between environment, culture, and mental health.


Skills Demonstrated
    - Writing advanced SQL queries using filtering, CASE, aggregation, and JOINs
    - Conducting exploratory analysis with real-world social science data
    - Translating academic findings into SQL-driven insights

Live Project
You can view the full project notebook and results on DataCamp:
[ Analyze Students' Mental Health - DataCamp](https://app.datacamp.com/learn/projects/1593)
