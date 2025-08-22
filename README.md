# 1. Create a string with your name and print it
name = "Nakul"
print("1:", name)

# 2. Find the length of the string "Hello World"
string = "Hello World"
print("2:", len(string))

# 3. Slice the first 3 characters from the string "Python Programming"
text = "Python Programming"
print("3:", text[:3])

# 4. Convert the string "hello" to uppercase
word = "hello"
print("4:", word.upper())

# 5. Replace "apple" with "orange" in the string
fruit_sentence = "I like apple"
print("5:", fruit_sentence.replace("apple", "orange"))

# 6. Create a list with numbers 1 to 5 and print it
numbers = [1, 2, 3, 4, 5]
print("6:", numbers)

# 7. Append the number 10 to the list [1, 2, 3, 4]
mylist = [1, 2, 3, 4]
mylist.append(10)
print("7:", mylist)

# 8. Remove the number 3 from the list [1, 2, 3, 4, 5]
mylist2 = [1, 2, 3, 4, 5]
mylist2.remove(3)
print("8:", mylist2)

# 9. Access the second element in the list ['a', 'b', 'c', 'd']
letters = ['a', 'b', 'c', 'd']
print("9:", letters[1])

# 10. Reverse the list [10, 20, 30, 40, 50]
nums = [10, 20, 30, 40, 50]
nums.reverse()
print("10:", nums)

# 11. Create a tuple with elements 100, 200, 300 and print it
tup = (100, 200, 300)
print("11:", tup)

# 12. Access the second-to-last element of the tuple
colors = ('red', 'green', 'blue', 'yellow')
print("12:", colors[-2])

# 13. Find the minimum number in the tuple
nums_tup = (10, 20, 5, 15)
print("13:", min(nums_tup))

# 14. Find the index of the element "cat"
animals = ('dog', 'cat', 'rabbit')
print("14:", animals.index("cat"))

# 15. Create a tuple containing fruits and check if "kiwi" is in it
fruits = ("apple", "banana", "mango")
print("15:", "kiwi" in fruits)

# 16. Create a set with 'a', 'b', 'c' and print it
myset = {'a', 'b', 'c'}
print("16:", myset)

# 17. Clear all elements from the set
set1 = {1, 2, 3, 4, 5}
set1.clear()
print("17:", set1)

# 18. Remove the element 4 from the set
set2 = {1, 2, 3, 4}
set2.remove(4)
print("18:", set2)

# 19. Find the union of two sets
set3 = {1, 2, 3}
set4 = {3, 4, 5}
print("19:", set3.union(set4))

# 20. Find the intersection of two sets
set5 = {1, 2, 3}
set6 = {2, 3, 4}
print("20:", set5.intersection(set6))

# 21. Create a dictionary with keys "name", "age", "city"
person = {"name": "Nakul", "age": 20, "city": "Delhi"}
print("21:", person)

# 22. Add a new key-value pair to dictionary
person2 = {'name': 'John', 'age': 25}
person2['country'] = "USA"
print("22:", person2)

# 23. Access the value of key "name"
person3 = {'name': 'Alice', 'age': 30}
print("23:", person3["name"])

# 24. Remove the key "age" from dictionary
person4 = {'name': 'Bob', 'age': 22, 'city': 'New York'}
del person4['age']
print("24:", person4)

# 25. Check if key "city" exists in dictionary
person5 = {'name': 'Alice', 'city': 'Paris'}
print("25:", "city" in person5)

# 26. Create a list, tuple, and dictionary, and print them all
mylist3 = [1, 2, 3]
mytuple3 = (4, 5, 6)
mydict3 = {"a": 1, "b": 2}
print("26:", mylist3, mytuple3, mydict3)

# 27. Create a list of 5 random numbers and sort in ascending order
import random
rand_nums = [random.randint(1, 100) for _ in range(5)]
rand_nums.sort()
print("27:", rand_nums)

# 28. Create a list with strings and print element at 3rd index
words = ["apple", "banana", "cherry", "date", "fig"]
print("28:", words[3])

# 29. Combine two dictionaries
dict1 = {"a": 1, "b": 2}
dict2 = {"c": 3, "d": 4}
combined = {**dict1, **dict2}
print("29:", combined)

# 30. Convert a list of strings into a set
str_list = ["apple", "banana", "apple", "cherry"]
print("30:", set(str_list))
