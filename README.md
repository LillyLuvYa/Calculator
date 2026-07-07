print("Welcome to grade checker 2.10!")
# This is the title of the program, it will be displayed when the program is run.
name = input("Enter the students name:")
# asks for Students name and stores it in the variable name
Assignment = float(input("Assignment grade: "))
#asks for assignment grade and stores it in the variable Assignment
quiz = float(input("Quiz grade: "))
#asks for quiz grade and stores it in the variable quiz
test = float(input("Test grade: "))
#asks for test grade and stores it in the variable test
average = (Assignment + quiz + test) / 3
# calculates the average of the three grades and stores it in the variable average
print("\nStudent name:", name)
print("Average grade:", average)
# This will print the students name and average grade
if average < 0 or average > 100:
    print("Error: Average grade must be between 0 and 100.")

elif average >= 90:
    print("Letter grade: A")
    print("Excellent work!")
elif average >= 80:
    print("Letter grade: B")
    print("Good job!")  
elif average >= 70: 
    print("Letter grade: C")
    print("You passed!")
else:
    print("Letter grade: F")
    print("damn are you serious? You failed!")
