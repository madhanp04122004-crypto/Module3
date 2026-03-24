🧹 Strings-Remove Nth Index Character from a String
🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

🧠 Algorithm
Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.
💻 Program
def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)
Output
image
Result
Thus the program has been successfully executed
