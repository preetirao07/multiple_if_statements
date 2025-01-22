# multiple_if_statements
# multiple if statements
print("Welcome to the rollercoster!")

height = int(input("What is your height in cm?\n"))


if height >= 120:

  print("Hello!")
  
  age = int(input("What is your age?"))
  
  if age < 12:
  
    bill = 5
    
    print("Please pay $5")
    
  elif age <12>18:
  
    bill = 7
    
    print("Please pay $7")
    
  else:
  
    bill = 12
    
    print("Please pay $12")
    
  photo= input("Do you want photo on the ticket? Type Y or N.")
  
  if photo =="Y":
  
    # add $3 extra to the bill
    
    bill += 3
    
  print(f"Your final bill is ${bill}")
  
else:

  print("Sorry! You cannot ride the rollercoster")
