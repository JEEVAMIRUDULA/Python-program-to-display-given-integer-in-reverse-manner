# Python-program-to-display-given-integer-in-reverse-manner
number = int(input("Enter a positive integer: "))
rev = 0

while number != 0:
    digit = number % 10
    rev = (rev * 10) + digit
    number = number // 10

print("Reversed number is:", rev)

Output:
Enter a positive integer: 56
Reversed number is: 65

