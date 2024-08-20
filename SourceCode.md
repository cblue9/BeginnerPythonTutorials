# Compound Interest Tutorial
# Caylin Blue

# P
principal_amount = float(input('Enter the amount originally deposited into the account: '))
# r
annual_interest = (float(input('Enter the annual interest rate paid by the account: '))) / 100
# n
compound_yearly = int(input('Enter the number of times per year that the interest is compounded: '))
# t
years = int(input('Enter the number of years the account will be left to earn interest: '))

# A
amount = principal_amount * (1 + (annual_interest / compound_yearly)) ** (compound_yearly * years)

print(f'There will be ${amount:.2f} after {years} years.')ing CompoundInterestTutorial.py…]()
