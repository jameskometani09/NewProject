list

data = []
while true:
name =  input("enter the name: ")
data.append(name)
choice = input("enter another name?: (y/n) : ")
if choice.casefold() == 'n':
break
for element in data:
print(element)

parallel list

names = ["Name1", "Name2", "Name3", "Name4"]
ages = [1, 2, 3, 4]
for i in range(len(names)):
  print(f"{names[i]} is {ages[i]} years old.")

def name():
  print(f"{names[i]} is {ages[i]} years old.")
  
