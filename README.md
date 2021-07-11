# Tuple-method
tuple=(1,2,3)
print(tuple)

# Allow Duplicates
tuple = ("0", "1", "2", "1", "0")
print(tuple)

# length ,len()
tuple = tuple(("Lilac", "White", "Skyblue", "Yellow", "Pink", "Green", "orange"))
print(len(tuple))

# One item tuple, remember the comma

tuple = ("kabira",)
print(type(tuple))

#NOT a tuple
tuple = ("raabta")
print(type(tuple))

# Tuple Items - Data Types
# string, int and boolean data types:
tuple1 = ("O", "N", "E")
tuple2 = (1, 2, 3, 4, 5)
tuple3 = (True, False, False)

print(tuple1)
print(tuple2)
print(tuple3)

tuple1 = ("abc", 34, True, 40, "male")
print(tuple1)

# Type ,type()
tuple = ("speed", "race", "distance")
print(type(tuple))

# Tuple ()
tuple = tuple(("eyes", "ears", "nose"))
print(tuple)

# Access Tuple Items
tuple = ("tablets", "mobile", "laptops")
print(tuple[1])

# Negative Indexing
thistuple = ("foundation", "concelar", "primer")
print(thistuple[-1])

# Range of Indexes
tuple = ("mode", "fan speed", "timer", "turbo", "swing", "temperature", "sleep")
print(tuple[2:5])

# Range of Negative Indexes
tuple = ("red", "orange", "pink", "black", "grey", "white", "yellow")
print(tuple[-4:-1])

# Check if/else Item Exists
tuple = ("cauliflower", "cucumber", "spinach")
if "cauliflower" in tuple:
  print("Yes, it's a vegetable tuple")
else:
  print("No, it's not a vegetable tuple")

# Change Tuple Values
x = ("Dance", "Jump", "Grove")
y = list(x)
y[1] = "Music"
x = tuple(y)

print(x)

# Add append()
tuple1 = ("apple", "banana", "cherry")
y = list(tuple1)
y.append("orange")
tuple1 = tuple(y)

print(tuple1)

# Add tuple to a tuple
tuple = ("apple", "banana", "cherry")
y = ("orange",)
tuple += y

print(tuple)

# Loop Through a Tuple
tuple = ("red", "yellow", "green")
for x in tuple:
  print(x)

# Loop Through the Index Numbers
# range() ,len()

tuple = ("red", "blue", "green", "yellow")
for i in range(len(tuple)):
  print(tuple[i])

# Using a While Loop
tuple = ("one", "two", "three")
i = 0
while i < len(tuple):
  print(tuple[i])
  i = i + 1
  
  




















