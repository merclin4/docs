gender = input("What is your gender? ")
Height=float(input("Enter your height in centimeters: "))
Weight=float(input("Enter your Weight in Kg: "))
Height = Height/100
BMI=Weight/(Height*Height)
print("your Body Mass Index is: ",BMI)
if(BMI>0):
	if(BMI<=18.4):
		print("you are Underweight")
                print("You are with Malnutrition risk")
	elif(BMI>=18.5 and <=24.9):
		print("you are Normalweight")
                print("You are a Low Risk Person")
	elif(BMI>= 25 and <=29.9):
		print("you are Overweight")
                print("You are an Enhanced Risk Person")
	elif(BMI>=30 and <=34.9):
		print("you are ModeratelyObese")
                print("You are a Medium Risk Person")
        elif(BMI>=35 and <=39.9):
                print("you are SeverelyObese")
                print("You are a High Risk Person")
	else: print("you are VeryseverelyObese")
              print("You are a Very High Risk Person")
else:("enter valid details")
-----------------------------------------------------------------------------------------------
