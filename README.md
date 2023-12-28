#If the bill was $150.00, split between 5 people, with 12% tip. 

#Each person should pay (150.00 / 5) * 1.12 = 33.6
#Format the result to 2 decimal places = 33.60

#Tip: There are 2 ways to round a number. You might have to do some Googling to solve this.💪

#Write your code below this line 👇
print("Welcome To the Tip Calculator")

total_bil=input("What was the total bill? ")
total=int(total_bil)

tip=input("What percentange tip would yoyu like to give? 0, 10, 15, 20? ")

tipp=float(tip)

ti= tipp/100 +1



split_between=str(input("How many people to split the bill? "))
split=int(split_between)

am_each=((total//split) * ti)



print(f"each person should pay: {am_each}")
