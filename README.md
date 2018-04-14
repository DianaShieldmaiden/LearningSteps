# LearningSteps
All the exercises I have been working on to understand how python works. 

Beginner 

first_name='Andreas'
last_name='Exad'
full_name=first_name+" "+last_name
print(full_name)

#declaring the list, list elements can be of different data types

myList = [1,2,3,4,5,"hello"]

#print the entire list 
print (myList)

#print the third item (index starts from zero)
print (myList[2])

#print the last item 
print (myList[-1])

#assign myList (from index 1 to 4) to myList2 and print myList2
myList2 = myList[1:5]
print (myList2)

#modify the second item in mylist and print the updated list
myList[1] = 20
print (myList)

#append a new item
myList.append("How are you?")
print (myList)

#remove an item from the list
del myList[5]
print (myList)
