# Python-Traning-
# KBC Game
#Question 1
print("Question for ₹10,000:")
print("Which of the following is the largest planet in our solar system?")
print("A. Earth")
print("B. Mars")
print("C. Jupiter")
print("D. Saturn")
answer1 = input("Your Answer (A/B/C/D): ")

if answer1 == "C":
    print("Correct Answer")
else:
    print("Wrong Answer")
    exit()

#Question 2
print("Question for ₹20,000:")
print("Who is known as the Father of the Nation in India?")
print("A. Jawaharlal Nehru")
print("B. Mahatma Gandhi")
print("C. Subhas Chandra Bose")
print("D. B. R. Ambedkar")
answer2 = input("Your Answer (A/B/C/D): ")

if answer2 == "B":
    print("Correct Answer")
else:
    print(" Wrong Answer.")
    exit()

#Question 3
print("Question for ₹40,000:")
print("Who is the Chief Minister of Rajasthan?")
print("A. Bhajan Lal Sharma")
print("B. Rahul Gandhi")
print("C. Narendra Modi")
print("D. Vasundra ")
answer3 = input("Your Answer (A/B/C/D): ")

if answer3 == "A":
    print("Correct Answer")
else:
    print("Wrong Answer.")


 # Calculator

print("Select Operation:")
print("1. Addition (+)")
print("2. Subtraction (-)")
print("3. Multiplication (*)")
print("4. Division (/)")

choice = input("Enter choice (1/2/3/4): ")

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))


if choice == '1':
    result = num1 + num2
    print("Result:", result)
elif choice == '2':
    result = num1 - num2
    print("Result:", result)
elif choice == '3':
    result = num1 * num2
    print("Result:", result)
elif choice == '4':
    if num2 != 0:
        result = num1 / num2
        print("Result:", result)
    else:
        print("Error: Cannot divide by zero!")
else:
    print("Invalid Input")
