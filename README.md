# Categorizing-Student-Final-Grades
Categorizing Student Final Grades is a Python project designed to automate the categorization of student grades based on their scores in various assessments. The project leverages Python, utilizing libraries such as `pandas` for data manipulation and `random` for generating sample scores. This tool reads student data, calculates final grades, and classifies these grades into categories.

In this project, we use a pandas DataFrame to store and manipulate student grade data.

## Data Dictionary
* ID: The unique identifier for each student.
* Tugas: The score obtained by the student in assignments.
* UTS: The score obtained by the student in the mid-term exam.
* UAS: The score obtained by the student in the final exam.
* Nilai Akhir: The final grade of the student, calculated as a weighted sum of Tugas, UTS, and UAS.
* Description: The category of the final grade, such as "A", "A-", "B+, "B", "B-", "C+", "C", "C-", "D", or "E".

## Workflow
1. We create a ID
2. We generate score Tugas, UTS and UAS
3. Calculate the final grade (`Nilai Akhir`)
4. Categorization
5. Make to a Dataframe

## Final Output
You will see the printed output of each student's grade categorization and a DataFrame named Rekap_Nilai_Mahasiswa with the following structure:



