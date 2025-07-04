# Python-assignment-week-2
#appending a list
my_list=[]
my_list.append(10)
print('After append:',my_list)

my_list.append(20)
print('After append:',my_list)

my_list.append(30)
print('After append:',my_list)

my_list.append(40)
print('After append:',my_list)

#inserting a value
my_list.insert(1,15)
print (my_list)

#extending a list
Extension_list=[50,60,70]
my_list.extend(Extension_list)
print('List after extension:',my_list)
 
 # Removing an element from a list
del my_list[-1]
print('After removing:',my_list)

# sorting in ascending order
my_list.sort()
print(my_list)

#finding the index of 30
index_of_30 = my_list.index(30)
print(index_of_30)
