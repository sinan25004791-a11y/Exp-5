PYTHON-LAB-EXPERIMENT-5

PYTHON PROGRAMMING LAB EXPERIMENT 5

Aim

To write a Python program to demonstrate tuple and related functions/operations such as len0, maxi, minO, sumO countO, indexi, sortedi, reversedo, membership operator, and conversion between tuple and list.

ALGORITHM 

1.Start the program.

2.Create a tuple t containing integer elements

3.Display the original tuple.

4.Access and display the first element using index 0.

5.Access and display the last element using index -1.


6.Find and display the length of the tuple using lenO.

7.Find and display the maximum element using maxi.

8.Find and display the minimum element using mino.

9.Calculate and display the sum of elements using sumo.

10. Check whether 10 is present in the tuple using the in operator.
    
11 Count the occurrence of 20 usina counto.

12.Find the index position of 50 using index)

13.Sort the tuple elements using sorted.

14.Reverse the tuple using reversed and convert it back to a tuple.

15.Convert the tuple into a list using listo.

16. Convert the list back into a tuple using tuple.
    
18. Display all the results.
    
18.Stop the program

source code


# Write a Python program to demonstrate tuple and related function operation

t = (10, 30, 20, 50, 40)

print()
print("****************************************************")

print("Original tuple : ", t)
print()
print("****************************************************")

print("first element of tuple : ", t[0])
print()
print("****************************************************")

print("last element of tuple : ", t[-1])
print()
print("****************************************************")

print("Length of the tuple : ", len(t))
print()
print("****************************************************")

print("Maximum element in tuple : ", max(t))
print()
print("****************************************************")

print("Minimum element in tuple : ", min(t))
print()
print("****************************************************")

print("Sum of elements in tuple : ", sum(t))
print()
print("****************************************************")

print("is 10 present in t : ", 10 in t)
print()
print("****************************************************")

print("Count of 20 in tuple : ", t.count(20))
print()
print("****************************************************")

print()
print("****************************************************")

print("Index of 50 in tuple : ", t.index(50))
print()
print("****************************************************")

print("Sorted tuple : ", sorted(t))
print()
print("****************************************************")

print("Reversed tuple : ", tuple(reversed(t)))
print()
print("****************************************************")

print("converting the tuple into list")
l = list(t)
print("after converting into list", l)
print()
print("****************************************************")

print("converting the list into tuple")
t1 = tuple(l)
print("after converting into tuple", t1)


output
****************************************************

Original tuple : (10, 30, 20, 50, 40)

****************************************************

first element of tuple : 10

****************************************************

last element of tuple : 40

****************************************************

Length of the tuple : 5

****************************************************

Maximum element in tuple : 50

****************************************************

Minimum element in tuple : 10

****************************************************

Sum of elements in tuple : 150

****************************************************

is 10 present in t : True

****************************************************

Count of 20 in tuple : 1

****************************************************

Index of 50 in tuple : 3

****************************************************

Sorted tuple : [10, 20, 30, 40, 50]

****************************************************

Reversed tuple : (40, 50, 20, 30, 10)

****************************************************

converting the tuple into list

after converting into list [10, 30, 20, 50, 40]

****************************************************

converting the list into tuple

after converting into tuple (10, 30, 20, 50, 40)


