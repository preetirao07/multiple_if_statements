# multiple_if_statements: 1
**Roller coster Tickets**
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


# multiple if statements: 2
**Burger delivery project**

print("Welcome to the burger hub!")

burger_size = input("What is the size of burger you want to order? S, M or L:")

if burger_size =="S":

    bill == 50
    
    print("Your bill is $50")
    
elif burger_size=="M":

    bill += 30
    
    print(f" Your bill is ${bill}")
    
elif burger_size=="L":

    bill += 20
    
    print(f" Your bill is ${bill}")
    
burger_type = input("Do you want veg burger? Y or N:\n")

if burger_type=="Y":

    bill += 0
    
elif burger_type=="N":
    bill += 50
    print(f"Your bill is {bill}")

extra_cheese = input("Do you want extra cheese? Y or N:\n")

if extra_cheese=="Y":

    bill +=20
    
    print(f"Your bill is ${bill}")
    
elif extra_cheese=="N":

    bill += 0
    
    print(f"Your bill is ${bill}")
    
else:

    print("You have provided wrong input")
