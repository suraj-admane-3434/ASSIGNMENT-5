# ASSIGNMENT-5

# Task 1: Create a Dictionary of Student Marks
student_marks = {
    "Amit": 85,
    "Sneha": 92,
    "Ravi": 78,
    "Priya": 88,
    "Neha": 95
}

student_name = input("Enter the student's name to get their marks: ")

if student_name in student_marks:
    print(f"{student_name}'s marks: {student_marks[student_name]}")
else:
    print("Student not found in the record.")

# Task 2: Demonstrate List Slicing
numbers = list(range(1, 11))
first_five = numbers[:5]
reversed_five = first_five[::-1]

print("\nFirst five elements of the list:", first_five)
print("Reversed first five elements:", reversed_five)

######################################################################################################################################################################
