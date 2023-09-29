1. Write script to create database
- class
- professor: one - many with class
- student: many - many with class
- course: one - many with class
- room: one - one with class

2. Query bellow:
- những cặp student-professor có dạy học nhau và số lớp mà họ có liên quan
những course (distinct) mà 1 professor cụ thể đang dạy
- những course (distinct) mà 1 student cụ thể đang học
- điểm số là A, B, C, D, E, F tương đương với 10, 8, 6, 4, 2, 0
- điểm số trung bình của 1 học sinh cụ thể (quy ra lại theo chữ cái, và xếp loại học lực (weak nếu avg < 5, average nếu >=5 < 8, good nếu >=8 )
- điểm số trung bình của các class (quy ra lại theo chữ cái)
- điểm số trung bình của các course (quy ra lại theo chữ cái)


3. Case: https://leetcode.com/problems/capital-gainloss/description/

4. Union/Union all: https://leetcode.com/problems/count-salary-categories/ 
