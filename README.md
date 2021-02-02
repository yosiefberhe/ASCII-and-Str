# ASCII-and-Str


str1='30//6'

num1=eval(str1)

print("The answer is " + str (num1))

city=input("Please enter your favourite city in a lowercase: ")

x=city[0]

print("Your favourite city is: " + city)

print("The first letter of your favourite city is: "+ x)

print("The ASCII code for your favourite city is: " + str(ord(x)))

print("The letter " + x + " occurs " + str(city.count(x)) + " times.")

string = city.upper()[:4]

new_string = string.center(30, '*')

print("The first 4 words Centered and Uppercase: ", new_string)
