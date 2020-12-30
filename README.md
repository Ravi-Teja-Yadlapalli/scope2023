# scope2023

Python code for the difference between the sum of the squares of the first one hundred natural numbers and the square of the sum

def sum_square_difference(n):
    return (((n**2) * (n + 1)**2) / 4) - (n * (n + 1) * (2*n + 1) / 6)

print(int(sum_square_difference(100)))
