# PythonBasic-Project-2
By using python programming language

# Check Even or Odd: 
# Determine if a given number is Even or Odd.
# Even Number :- -2,-4,-6,-8,-10,.....,2,4,6,8,10,.....,n.
# Odd Number :- -1,-3,-5,-7,-9,-11,....,1,3,5,7,9,11,.....,n.

# Even Number Section

print("Program for even number .\n")

# User input it's we get for set the starting point and ending point of numbers to checkout Even or Odd numbers between this number .

starting_point = (int(input("Enter the number for starting point of an even number : ")))

ending_point = (int(input("Enter the number for ending point of an even number : ")))

# For loop is used to compare each and every numbers between the user inputed numbers .

for even_number in range (starting_point , ending_point + 1 , 2) :
    print(even_number)

# Odd Number Section .

print("Program for odd number .\n")

starting_point = 1

ending_point = (int(input("Enter the number for ending point of an odd number : ")))

# User input it's we get for set the starting point and ending point of numbers to checkout Even or Odd numbers between this number .

for odd_number in range (starting_point , ending_point + 1 , 2) :
    print(odd_number)
