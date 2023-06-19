# below codes
print("Welcome to the rollercoaster!")
height = int(input("What is your height in cm? "))
bill = 0
# to check if the height meets the requirement?
if height >= 120:
  print("you can ride the rollercoaster!.")
  # To check for age if height is valid
  age = int(input("What is your age?"))
  if age < 12:
    bill = 5
    print(f"Child ticket is ${bill}.")
  elif age <= 18:
    bill = 7
    print(f"Youth ticket is ${bill}.")
  else:
    bill = 12
    print(f"Adult ticket is ${bill}.")
# to added other services by the user e.g photo
  photo = input("Do you want to take photo? Y or N. ")
  if photo == "y":
    bill += 3 # this add 3 to the varible bill
    print(f"Your total bill is ${bill}.")
  
else:
  print("Sorry, you need to grow taller")
