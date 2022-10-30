The Faculty needs a section-wise Number of candidates who have secured more than or equal to 75
marks in the Semester Exam.
Note: Enrollment No. is declared as Primary Key
Steps
1. Create table Students (e.g in MS Access) 
2. Write column names and set Enrollment_No as Primary Key
3. Fill the table with students data
4. To know the above specified number of candidates use the following SQL Command:
SELECT Section, COUNT(*) AS No_Of_Candidate_greater_than_or_equal_to_75_marks
FROM Students
WHERE Marks >= 75
GROUP BY Section;

