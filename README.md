# tuple_list_number_input
# A program that accepts a sequence of comma-separated numbers from the user and places then in a list and a tuple of those numbers.

x, y, z =input("Enter three values (in this fasion:1, 2, 3) : ").split()

#print(x, y, z)

lst_input = [x, y, z]

tpl_input = (x, y, z)

print(lst_input)
print(tpl_input)
