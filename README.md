# Precourse-Notes

"""Basic Arithmetic Operators"""


# The '+' and '-' operators do what you expect
print("1 + 7 =", 1 + 7)
print("3 - 5 =", 3 - 5)
print() # Empty print statements are used as linebreaks here, for readability in the output


# So does '*'
print("9 * 33 =", 9 * 33)
print()


# Multiplication of an int by a 'float' results in a 'float'
print("1.0 * 7 =", 1.0 * 7)
print("type:", type(1.0 * 7))
print()


# Q: what's wrong with this expression '9(33 + 6)' ?
# A: multiplication REQUIRES the '*' operator to be used explicitly
# Uncomment the line below and click 'run' to see the error
# print(9(33 + 6))


# Division of 'int' objects ALWAYS results in a 'float'
print("7 / 5 =", 7 / 5)
print("type:", type(7 / 5))
print()


# Even if the result is an integer - note the difference between the words 'int'
# (referring to the type), and 'integer' (referring to the mathematical definition)
print("4 / 2 =", 4 / 2)
print("type:", type(4 / 2))
print()


# The exponentiation operator '**' does what you expect
print("2**3 =", 2**3)
print("5.32**5 =", 5.32**5)
print()


# You can also evaluate roots with the exponentiation operation
# (Square root is equivalent to exponentiation by 1/2, for example)
# Notice that when exponentiating by a fraction (taking a root), it always returns a 'float'
print("16**(1/2) =", 16**(1/2))
print("16**0.5 =", 16**0.5)
print()


# Python follows order of operations when using parenthesis (just like in real life)
print("7 + 3**3 * 9 / 36 =", 7 + 3**3 * 9 / 36)
print("(7 + 3**3) * 9 / 36 =", (7 + 3**3) * 9 / 36)
print()


"""
Galvanize Data Science Prep
https://www.galvanize.com/data-science/prep
"""
