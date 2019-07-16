#Creating a tuple
lunch_menu=("Welcome Drink","Veg Starter","Non-Veg Starter","Veg Main Course","Non-Veg Main Course","Dessert")

#These are also valid
sample_tuple="A","B","C"
sample_tuple1=("D",)

#Length of the tuple
print("Number of elements in the tuple, lunch_menu:",len(lunch_menu))

#Random read
print("Element at 2nd index position in lunch_menu:", lunch_menu[2])

print("Concatenating tuples:")
#Concatenating two tuples
sample_tuple=sample_tuple+sample_tuple1 #This will create a new tuple by combining the elements of existing sample_tuple and sample_tuple1
print(sample_tuple)

#Adding a single element to a tuple
sample_tuple=sample_tuple+("E",)  # This will also create a new tuple, sample_tuple
print(sample_tuple)


#Adding multiple elements to a tuple
sample_tuple=sample_tuple+("F","G")  # This will also create a new tuple, sample_tuple
print(sample_tuple)

print("Iterating the tuple using range()")
for index in range(0,len(lunch_menu)):
    print(lunch_menu[index])

print("Iterating the tuple using keyword in")
for food_type in lunch_menu:
    print(food_type)

print("Searching for an element in tuple")
if "Dessert" in lunch_menu:
    print("Dessert is there")
else:
    print("Dessert is not there")        

#Slicing a tuple
print("Tuple slice using positive indices:",lunch_menu[1:5])

print("Tuple slice using negative indices:",lunch_menu[-5:-1])

# comment the below code and try to visualize.
lunch_menu[0]="" #This line will result in an error, i.e., tuple is immutable
print(lunch_menu)
