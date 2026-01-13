# reversing-integers-62-100

number = int(input("Enter a positive integer: "))
rev = 0

while number != 0:
    digit = number % 10
    rev = (rev * 10) + digit
    number = number // 10

print("Reversed number:", rev)
