# Body-Mass-Index-calculator-
this is a simple program that helps calculate BMI using weight in kg and height in meters 

#my fist python program
#This is to calculate Body Mass Index

def calculate_bmi(weight, height):
    bmi = weight / (height ** 2)
    return bmi

weight = float(input("Enter your weight in kilograms: "))
height = float(input("Enter your height in meters: "))

bmi = calculate_bmi(weight, height)
print("Your BMI is:", bmi)


#if statement

if bmi<=17:
   print("YOu are underweight")
elif bmi<=24:
    print("YOu are normal weight")
elif bmi<=29:
    print("YOu are overweight")
elif bmi<=39:
    print("YOu are obese")
elif bmi<=49:
    print("YOu are siverly obese")
else:
    print("you dont have result")
