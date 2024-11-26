# Create an empty list
my_list = []

# Appending elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert the value 15 
my_list.insert(1, 15)

# Extend ny created list with another list
my_list.extend([50, 60, 70])

# Remove the last element from the list
my_list.pop()

my_list.sort()

index_of_30 = my_list.index(30)
print(f"The index of 30 is: {index_of_30}")
