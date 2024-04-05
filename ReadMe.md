*Specifications related to the project*
1. User should be able to search for a student by entering part of the name.
    
    Solution:
        Using a linq query to select students that have names that CONTAINS the input
        List<Student> search = students.Select(x => x.contains(input)); Something like this

2. User can select a course from a list, and view all the students that took this course and
their grade.

    Solution:
        



3. User should be able to select a grade and show all the grades in the database equal to
or better than this grade, including the student that received the grade and the relevant
course.


4. User should be able to get a list of all the students who failed, and which courses they
have failed in.


5. Users should be able to manage students’ participants in a course (i.e., add/remove
students from it). [Note that the grade is mandatory, the current database schema
doesn’t allow a student to be assigned to a course at some time, and then the grade
assigned later. Neither will the grade be preserved if a user is removed from a course]
