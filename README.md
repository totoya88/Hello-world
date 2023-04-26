
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

number = 5
print("Factorial of", number, "is", factorial(number))

# A program to count the number of vowels in a string
def count_vowels(string):
    vowels = "aeiouAEIOU"
    count = 0
    for char in string:
        if char in vowels:
            count += 1
    return count

text = "Hello World"
print("Number of vowels in", text, "is", count_vowels(text))
