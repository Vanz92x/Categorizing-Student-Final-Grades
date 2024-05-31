# Categorizing-Student-Final-Grades
Categorizing Student Final Grades is a Python project designed to automate the categorization of student grades based on their scores in various assessments. The project leverages Python, utilizing libraries such as `pandas` for DataFrame to store and manipulate student grade data, and `random` for generating sample scores. This tool reads student data, calculates final grades, and classifies these grades into categories.

## Data Dictionary
* ID: The unique identifier for each student.
* Tugas: The score obtained by the student in assignments.
* UTS: The score obtained by the student in the mid-term exam.
* UAS: The score obtained by the student in the final exam.
* Nilai Akhir: The final grade of the student, calculated as a weighted sum of Tugas, UTS, and UAS.
* Description: The category of the final grade, such as "A", "A-", "B+, "B", "B-", "C+", "C", "C-", "D", or "E".

## Workflow
1. Create an ID for each student.
2. Generate scores for Tugas, UTS, and UAS.
3. Calculate the final grade (Nilai Akhir).
4. Categorize the final grade.
5. Create a DataFrame to store the data.

## Final Output
The final output includes the printed categorization of each student's grade and a DataFrame named Rekap_Nilai_Mahasiswa with the following structure:
<div align="center">
  <img src="https://github.com/Vanz92x/Categorizing-Student-Final-Grades/assets/165736197/9661c987-9144-4f03-80bd-8ecf6b03e08c" alt="DataFrame Structure" />
</div>



