## NAME: DEEPIKA P
## REGISTER NO: 212223240024
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program using class and function to compute the area of a circle, taking radius as input from the user.

## 🧠 Algorithm
1. Define a class named Circle.

2. Inside the class, define an __init__ method to initialize the radius.

3. Define a method area() to compute the area using the formula:
 
      (Use 3.1416 or math.pi)

4. In the main program:

5. Take radius input from the user.

6. Create an object of the Circle class with the given radius.

7. Call the area() method and print the result.
## 🧾 Program
class pen():\
    def stationary(self,r):\
        area=(3.141592)*r*r\
        print("Area of circle:",round(area,2))\
c=pen()\
r=int(input())\
c.stationary(r)

## Output
![Screenshot 2025-05-18 203430](https://github.com/user-attachments/assets/e69e69f2-291b-4a88-bccf-ddb759b2aba9)

## Result
The program successfully calculates the area of a circle using class and function, with the radius provided by the user.

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}\
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

dict3 = {**dict1, **dict2}\
print(dict3)

## Output
![Screenshot 2025-05-18 203832](https://github.com/user-attachments/assets/dabb950b-d329-48c5-871b-d2aa65c7b872)

## Result
The program successfully merged two dictionaries. If duplicate keys existed, the value from the second dictionary replaced the value from the first.


# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values


## 🎯 Aim
To write a Python program that sorts the keys and values in a dictionary in ascending order using the keys.

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

## 🧪Program
def dictionairy():\
    key1={}\
    key1[1]=2\
    key1[2]=56\
    key1[3]=323\
    key1[4]=24\
    key1[5]=12\
    key1[6]=18\
    print("Keys and Values sorted in alphabetical order by the key ")\
    for i in sorted(key1):\
        print((i,key1[i]),end=" ")\
def main():\
    dictionairy()\
if __name__ == "__main__":\
    main()

## Sample Output
![Screenshot 2025-05-18 204106](https://github.com/user-attachments/assets/792386f8-342b-4e6a-8b80-11f114b10a7d)

## Result
The program successfully sorted the dictionary based on keys and displayed the key-value pairs in the required format.

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
try:\
    n=int(input())\
    a=[]\
    for i in range(n):\
        x=int(input())\
        a.append(x)\
    print(a)\
    print(a[6])
                
                
except:
        print("6 is not accepted")

## Output
![Screenshot 2025-05-18 204552](https://github.com/user-attachments/assets/53a87958-a1f9-4acd-a501-63e80399bc1d)

## Result
The program successfully demonstrates exception handling by catching an IndexError when accessing an invalid index and printing a custom error message.

# File Handling in Python: Write a Python program to read a file and count the number of words in it.

## 🎯 Aim
To write a Python program that reads a file and counts the number of words present in it.


## 🧠 Algorithm
1. Define a function create_file(file_path, content) to create a file and write the given content into it.

2. Define a function count_words_in_file(file_path) to count words in the file:

     Open the file in read mode.

     Initialize a word counter to zero.

    Read the file line by line.

    Split each line into words using whitespace.

    Increment the counter by the number of words in each line.

    Return the total count.

3. Get input string for file content from the user.

4. Call create_file() to create and write to the file.

5. Call count_words_in_file() and print the result.

## 🧾 Program
def create_file(file_path,file_content):\
    with open(file_path,'w') as file:\
        file.write(file_content)\
def count_words_in_file(file_path):\
    with open(file_path,'r') as file:\
        content=file.read()\
        words=content.split()\
        return len(words)
## Output

![Screenshot 2025-05-18 204929](https://github.com/user-attachments/assets/c9fcb660-ed9c-4d25-8831-7cb3fd727506)

## Result
The program correctly reads the file and counts the total number of words, displaying the count to the user.





