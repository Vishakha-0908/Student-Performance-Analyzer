# Student-Performance-Analyzer

1. Project Overview
   
The Student Performance Analyzer is a Python-based project designed to help schools analyze and monitor the academic performance of students. The project collects student data, processes it using NumPy and Pandas, and applies Object-Oriented Programming (OOP) concepts to manage and analyze student records efficiently. It also includes exception handling to ensure robust execution.

2. Objectives
   
  •	Collect and store student data (name, roll number, age, class, and marks).

  •	Calculate individual and class-level performance metrics.

  •	Identify top and bottom performers.

  •	Generate structured reports in CSV format.

  •	Apply OOP principles for clean and scalable code.

  •	Handle invalid inputs and file errors gracefully.

3. Tools & Technologies
   
  •	Programming Language: Python

  •	Libraries: NumPy, Pandas

  •	Concepts Applied: Object-Oriented Programming (OOP), Exception Handling

  •	Output: Console output, Pandas DataFrame, CSV reports

4. Project Modules

4.1 Student Class

  •	Attributes: name, roll_no, age, student_class, marks
 
  •	Methods:
                   
                    1.display_details(): Prints student info and marks
                  
                    2.calculate_grade(): Returns grade based on average marks


4.2 Classroom Class
  
  •	Stores multiple Student objects
  
  •	Methods:
            
             1.add_student(), remove_student()
          
             2.overall_performance(): Returns mean, median, and standard deviation of class marks
            
             3.to_dataframe(): Converts data into Pandas DataFrame for analysis


5. Key Functionalities

  •	Accepts student data from user input.

  •	Uses NumPy arrays for calculations: average marks, highest/lowest marks, class statistics.
 
  •	Uses Pandas for:
          
           o	Top 5 and bottom 5 performers
          
           o	Grouping by class for average marks
          
           o	Exporting CSV report for record-keeping

•	Implements exception handling for:
          
          o	Invalid input (e.g., strings instead of numbers)
         
          o	File handling errors


6. Sample Output

Overall Class Performance:

  •	Mean Marks: 85.03

  •	Median Marks: 88.0

  •	Standard Deviation: 10.16
            
            Top 5 Students: Vishakha, Vaishnavi, Nimish, Vinit, Jayanti
            
            Bottom 5 Students: Jagruti, Yadnesh, Shreeya, Swara, Harshal

            CSV Report: Saved as student_report.csv with all student details, averages, and grades.

7. Learning Outcomes

   •	Strengthened understanding of Python, NumPy, and Pandas for data processing.

   •	Learned to apply OOP concepts for scalable and maintainable code.

   •	Gained experience in data-driven insights and reporting.

   •	Enhanced problem-solving skills through exception handling.

8. Conclusion

The Student Performance Analyzer is a complete Python project that demonstrates practical application of programming, data analysis, and OOP concepts. It provides meaningful insights into student performance and can help educators make data-driven decisions.
