number = int(input("Enter a number: "))  # Prompt the user for a number

sum_even = 0  # Variable to store the sum of even numbers

for num in range(1, number+1):
    if num % 2 == 0:
        sum_even += num

print("The sum of even numbers from 1 to", number, "is", sum_even)
