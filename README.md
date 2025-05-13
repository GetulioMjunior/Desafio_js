# Desafio_js
Project Requirements:
Receive an array of student objects:

The program must receive a list of student records, where each student has a name and an array of grades.

Loop through the students:

The function must iterate over each student in the list explicitly using a for loop.

Do not use higher-order functions like map, reduce, or forEach — the code should use only a traditional for loop.

Calculate the average of the grades:

For each student, the function must calculate the average of their grades by summing all the grades and dividing by the number of grades.

The average should be rounded to the nearest whole number.

Add two new properties to each student:

average: the rounded average of the student's grades.

status: the student's status, which should be "approved" if the average is greater than or equal to 60, and "failed" if the average is less than 60.

Return the updated array of students:

The function should return an object with two keys:

transformed: the array of students with the average and status properties added.

summary: a summary containing the number of approved and failed students.

Count approved and failed students:

After processing all students, the function must count how many were approved and how many failed, and include this information in the summary object.

Formatted JSON output:

The final output, when printed to the console, should be a well-formatted JSON string with indentation to improve readability. This can be done using JSON.stringify() with the appropriate formatting parameters.

Bonus Requirements:
Count of approved and failed students:

The code must be able to count how many students passed (average ≥ 60) and how many failed (average < 60), returning this information in the summary.

Let me know if you'd like a code implementation of this specification in JavaScript!
