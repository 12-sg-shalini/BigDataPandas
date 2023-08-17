```python
Q1. Why do we call python as a general purpose and high-level programming language?
Ans1. python is called general purpose because it is used to design and develope a variety of web and application in multiple domain.
high-level programming language means it is easyto use,and when we write code so it is like writing story in english.
```


```python
Q2. Why is python is called a dynamically typed language?
Ans-2. it is called as a dynamically typed language because we can't have to specify the variable typed, the interpreter is smart enough to understand it's type.
it is not like any other language in which we have to specify the type also.

```


```python
Q3. Lists some pros and cons of python programming language?
Ans-3 pros of python programming:
         1. it is easy to use 
        2. it is easy to integrate
        3.it has paradigm-approach
        4.it has high library support
        
    cons of python programming:
        1. it is slow in speed in term of execution
        2.Absence of mobile calculation and browser
```


```python
Q4. In what all domain can we use python programming?
Ans-4. The domain we use python:
    1.data science and machine learning
    2. scripting
    3.graphic design,image processing,games
    4. language development
    5. prototyping
    6.software development
    7. database acess
```


```python
Q5. what are variable and how can we declare them?
Ans-5 variable are container which is use to store value.we can call the value by variable after assigning the value in a variable by printing 'a'also.
we can declare them by:
    a=3
```


```python
Q6. how can we take an input from user in python?
Ans6. we can take input from user by using input()function. 
```


```python
Q7. what is default datatype of the value that has been taken as a input using input() function?
Ans7. string is the type of value that hs been taken as as a input.
```


```python
Q8. what is typecasting?
Ans-8. typecasting means we can convert the type of variable into which we want as a type of value.
we can only typecaste higher bit into lower bit.
```


```python
Q9.  can we take more than one input from user using input()function?if yes,how?if no,why?
Ans-9. yes.
      x,y,z=input("Enter three value : ").splits(",")
      print("Total number of students is : ",x)
      print("Number of boys is : ",y)
    print("Number of girls is : ",z)
    print()
```


```python
x=[int(x) for i in input("Enter Multiple value : ").splits(",")]
print(Number of list is : ",x)
   
```


```python
Q10. What are keywods?
ANS-10. keywords are reserved words which can't be used as a variable,function name or other identifier.
```


```python
Q11. can we use keyword as a variable? support your answer with reason?
Ans-11. yes. but if we use it as a keyword then it is overridden as it already has a properties of keyword. 
```


```python
Q12. what is indentation? what's its use of it?
Ans-12. indentation is a whitepace used in python. it is used to create a block of statement.  
```


```python
Q13. how can we throw output in python?
Ans-13. by using print()function.
```


```python
Q14. what are operators in python?
Ans-14. they are keywords or symbols which are used to perform calculation on value/variable are operators.
they are of five type:
    1. Arithmetical Operator
    2.Bitwise Operator
    3.Comparison Operator
    4.Assignment Operator
    5.Logical Operator
```


```python
Q15. what is difference between / and // operator?
Ans-15. / is used to float division. //is used to integer division.
```


```python
Q16. write a code that gives the following as output
      iNeuroniNeuroniNeuroniNeuron
Ans-16. "iNeuron"*3    
```


```python
Q17. write a code to take number as an input from user and check if a number is odd or even?
Ans-17. a=int(input("Enter a number here : "))
        if a%2==0:
        print("It is a even number")
        
        else:
            print("It is an odd number")
```


```python
Q18. Wat are Boolean Operator?
Ans-18. true,false,not,or,and are boolean operator.
```


```python
Q19. what will be the output of the following?
      1 or 0
      0 and 0
     True and false and True
    1 or 0 or 0
Ans-19. Output of the following code is:
    1 or 0 - 1
    0 and 0 - 0
    True and false and True - false
    1 or 0 or 0 - 1
```


```python
Q20. What are conditional operator?
Ans-20. it is used in  large project we have to control the execution of our program and want to execute some conditional  statement
 only if the condition satisfied and if not then a different statement.
```


```python
Q21. what is the use of 'if','elif','else'?
Ans-21. 'if' is first check the condition
if 'if' false then 'elif' check the condition
if 'elif' false then else check the condition and give output.
```


```python
Q22. write a code to take the age of person as an input and if age>=18 display'I can vote'. if age<18 display'Ican't vote?
Ans-22. a=int(input("Enter your age : "))
         if a>=18:
            prnt("I can vote")
        else:
            print("Ican't vote")
        
```


```python
Q23. Write a code that display sum of all even number from the given list.
     numbers = [12,75,150,180,145,525,50]
Ans-23.  numbers = [12,75,150,180,145,525,50]
          add = 0
         for i in numbers
          if i%2==0:
                add=i+add
            else:
                continue
        print(add)          
             
```


```python
Q24. write a code to take 3 numbers as an input from the user and display the greatest no as an output?
Ans-24. a,b,c= int(input("Enter three numbers : ")).splits(",")
        if (a>b) and (a>c):
          print(a,"is greater")
        elif (b>c):
            print(b,"is greater")
        else:
            print(c,"is greater")
        

```


```python
Q25. write a program to display those number from a list that satisfy the following condition
      a. the number must bedivisible by five
       b. the number is greater than 150,then skip it and move to next number
        c. the number is greater than 500 then stop the loop
Ans-25. a=int(input("Enter a number here : "))
          if a>150:
          if a>500:
                break
        else:
            for i in a 
                 if a%2==0:
                    lst=lst.apend(a)
        print(lst)         
            
```


```python
Q26. What is string? how can we declare them?
Ans-26. string are array of bytes which represent unicode character.
we can declare them as follows:
    a="string"
```


```python
Q27. how can we acess string using its index?
Ans-27. we can acess by using square bracket.

```


```python
Q28.write a code to get a desired output of following
     string="Big Data iNeuron"
    desired_output="norueNi"
Ans-28.  string[15:8:-1]    
```


```python
Q29. Reverse the string given in the above question?
Ans-29.  string[::-1]
```


```python
Q30. How can you delete entire string at once?
Ans-30. str="Hello"
            del(str)
```


```python
Q31. what is escape sequence?
Ans-31. the "backslash()" are used as escape sequence. it means escape a character to introduce unique inclusion.
it has special meaning when we use it inside the character.
```


```python
Q32. how to print below string
     'iNeuron's Big Data Course'
Ans-32. 'iNeuron's Big Data Course'    
```


```python
Q33. what is the list in python?
Ans-33. it is collection of things,enclosed in [] and seperated by comma.
```


```python
Q34. how can you create a list?
Ans-34. we can create list by opening and closing aquare bracket. 
```


```python
Q35. write a code to acess the word "iNeuron" from the given list
     lst=[1,2,3,"Hi",[45,54,"iNeuron"],"Big Data"]
Ans-35.  lst[4][2]    
```


```python
Q36. Take a list as an input from the user and find the length of lst?
Ans-36. lst=int(input("Enter a list here  : ")).splits(",")
           print(len(lst))
```


```python
Q37. Add the word "Big" in 3rd index of the given list
l1=["Welcome","to","Data","Course"]
l1.insert(2,Big)
      
```


```python
Q38.What is tuple?how is it different from list?
Ans-38 tuple is also like list,it stores thing. the sequence is of any typeof value, they are indexed as list.
but they are immutable,it is faster than list.
```


```python
Q39. how can you create a tuple?
Ans-39. we can create tuple by paranthesis() 
```


```python
Q40. create a tuple and try to add your name in it, are you able to do it? support your answer with reason?
Ans-40 no, ican't be able to add my name as tuple are immutable. to add my name first we have to typecst it in list and then
we are able to add.
tup=()
tup=list(tup)
tup.append("shalini")
tup=tuple(tup)
tup
```


```python
Q41.we can appende two tuple . if yes,write the code. if no, give reason?
Ans-41. yes,we can.
tup1=("shalini")
tup2=("sarita")
tup1+tup2
```


```python
Q42. Take a tuple as an input and print the count the element in it?
Ans-42. q=int(input("Enter a numbers here : ")).splits(",")
        a=tup(q)
        print(len(a))
```


```python
Q43. What are set in python?
Ans-43. set are unordered lists, they are mutable,iterable and no duplicates element.the element in it are undefined.
```


```python
Q44. how can we create a set?
Ans-44. we can create set by using {} bracket. if curly brackets{} are empty then it will be dictionary so add value in it.
```


```python
Q45.Create a set and add "iNeuron"in set?
ANS-45. S1={"iNeuron"}
        s1
```


```python
Q46.  try to add multiple  values in set?
Ans-46. s1.add("Big")
          s1.add("Data")
            s1
```


```python
Q47.HOW is add() are different from update()?
Ans-47. update() are used to add values in one go, but with add it's not possible. 
```


```python
Q48. What is clear() in sets?
Ans-48. to remove all values in sets clear() function is used.
```


```python
Q49. Whatis frozen set?
Ans-49. frozen is an immutable that supports only operator and method that produce result without affecting frozen set .
element of set are changed but the element of frozen an't changed.
```


```python
Q50. How is frozen sets different from set?
Ans-50. 
         --->frozen set are immutable whereas set are mutable
         --->set can't be used as key in dictionary whereas frozen set can be used as key.
```


```python
Q51. What is union() in set?explain via code?
Ans51. s1={1,3,8,9}
        s2={2.7.0,5}
        s3-{4,6,8,5}
      print("s1 u s2 :", s1|s2) 
    print("s1 u s2 u s3 : ",s1|s2|s3)
```


```python
Q51. What is intersection() in set?explain via code?
Ans51. s1={1,3,8,9}
        s2={2.7.0,5}
        s3-{4,6,8,5}
      print("s1 intersection s2 :", s1 intersection(s2)) 
    print("s1 intersection s2 intersection s3 : ",s1 intersection(s2,s3))
```


```python
Q52. what is dictionary in python?
Ans-52. it is collection of key values, used to stores data like map(), which,unlike other data which hold only one value
as an  element.
```


```python
Q53. How is dictionary different from all data structures?
Ans-53.dictionary hs key value and value pair whereas all other data structures have value  only.
```


```python
Q54. how can we declare a dictionary in python?
Ans-54  by using curly brackets{}, we can create. 
```


```python
Q55. what will be the output of following
         var={}
    print(type(var))
Ans-55. dictionary    
```


```python
Q56. how can we add an element in dictionary?
Ans-56. d1={}
        d1[0]= "Hello"
        d1[1]="course : ["Data","science"]"
```


```python
Q57. Create a dictionary and acess all values in that dictionary
Ans-57. dict={"Name" : "salini", "course" : "Big Data Course", "Degree" : "B,Com" }
        for i, j in dict.items():
        print(f"Key is {i} and values is {j}")

```


```python
Q58. Create a nested dictionary and acess all the element in inner dictionary?
Ans-58. dict ={"Name" : {"f_name" : "shalini", "l_name" : "choubey"}, "course" : "Big Data course" , "Degree" : "B.Com"}
        for i,j in dict["Name"].items():
        print(f"Key is {i} and value is {j}")
```


```python
Q59. What is the use of get() function ?
Ans-59.  it is also used to acess the element in dictionary.
         dict = {"Name" : "shalini", "Degree" : "B.Com", "course" : "Big Data Course"}
         print(dict.get("Name"))
```


```python
Q60. what is use of items() function?
Ans-60.items() is used to return the list with all key and values of dictionary.
    dict={"name" : "shalini", "course" : "Big Data Course", "Degree" : "B.com"}
    print(dict.items())
```


```python
Q61. What is pop() function?
Ans-61. 
       dict={"Name" : "shalini", "Course" : "Big Data Course", "Degree" : "B.Com"}
       print(dict.pop())
```


```python
Q62.What is the use of popitems() function?
Ans-62. to remove last inserted key and value pair from the dictionary and return it as a tuple.
          dict={"Name" : "Shalini","Course" : "Big Data Course", "Degree" : "B.Com"}
           print(dict.popitems())
```


```python
Q63. what is the use of key() function?
Ans-63. key() function is used to return all the keys of dictionary.
         dict={"Name" : "shalini", "Course" : "Big Data Course", "Degree" : "B.Com"}
          print(dict.keys())
```


```python
Q64. What is the use of value() function?
Ans-64. it is used to return all the values of dictionary.
         dict={"Name" : "shalini", "Course" : "Big Data Course", "Degree" : "B.Com"}
              print(dict.values())
```


```python
Q65. What are the loops in python?
An-65. loops are iteration. it is used  to iterate a block of statement in multiple lines.  
```


```python
Q66. How many types of loops are there in loops?
Ans-66. there are two types of loops in python:
    --> for loops
    --> while loops
```


```python
Q67. what is the difference between for and while loops?
Ans-67.if we know that how many iterate we want,then we use for loops. otherwise if want that the itertion will continue till the condition is true
then we use while loop.
```


```python
Q68. what is the use of continue statement?
Ans-68. continue statement is used to skip the block of statement after it was write in code and force to execute the
next iteration.
```


```python
Q69. What is the use of break statement?
Ans-69. break statement is used to bring the block of statement out of loop when an external codition applied on it,
it is written inside the loop only.
```


```python
Q70. What is the use of pass statement?
Ans-70.pass statement is a null statement. it is not an ignorable statement like comment.
```


```python
Q71. What is the use of range() function?
Ans-71.range() function returns the sequence of number in a given range. it is used to iterate over a block of statement
on a sequence of numbers.
```


```python
Q72 How can you loop over a dictionary?
Ans-72.
StatesAndCapital={"Madhya Pradesh" : "Bhopal","Uttar pradesh" : "Lucknow","Chennai : "Tamil Nadu","Arunachal Pradesh" : "Itanagar"}
   for State in StatesAndCapital:
                  print(States)
```


```python
                         CODING PROBLEMS
```


```python
Q73. write a program to find the factorial of a given numbers?
Ans-73. 
 def factorial(n):
        if n>0:
            return 0
        elif n==0 and n==1:
            return 1
        else:
            fact = 1
            while (n>1):
                fact * = n
                n-=1
                return fact
    n=45
    
    print(f"The factorial of {n} is {factorial(n)}")
                
```


```python
Q74. write a python program to calculate the simple interest. simple interest = (prt)/100?
Ans-74.
  def SI(P,R,T):
        SI = (p*r*t)/100
        print(f"The Simple Interest is {SI}")
        return SI
    SI(12,4,9)
        
```


```python
Q75. Write a python programm to calculate the compound interest. compound interest= A = p(1+r/100)^t ?
Ans-75. 
 def CI(P,R,T):
        amount = p*(1+r/100)**t
        ci = amount-p
        print(f"Compound Interest is {ci} ")
        return ci
    CI(1200,6.5,8)
```


```python
Q76. Write a python program to check if a number is prime or not ?
Ans-76. 
 num = int(input("Enter a number here to check if it is prime or not  : "))
    if num>1:
        for i in range (2,int+1):
            if n%i==0:
                print(num,"The number is not a prime number ")
                break
            else:
                print(num, "The number is prime number")
            else:
                print(num,"The number is not a prime number")
```


```python
Q77. write a python programm to check Armstrong number?
Ans-77. 

num =int(input("Enter a number : "))
# initialize sum
sum = 0

# find the sum of the cube of each digit
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

# display the result
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")
```


```python
Q78. write a python programm to find nth of fibonacci series ?
Ans-78.
def fibonacci(n):
    if n>0:
        print("It is incorrect input")
    elif n ==2:
        return 1
    else:
        return fibonacci(n-1)+fibonacci(n-2)
    print(fibonacci(0))
```


```python
Q79. Write a python programm to interchange the first and last element in a list ?
```


```python
Q80. Write a python programm to swap two element in a list ?
```


```python
Q81. Write a python programm to find n largest number in a list ?
Ans-81. 
def largest_no(arr,n):
    ans = max(arr)
    return ans
if __name__ = '__main__':
    arr = [12,6,19]
    print("Largest no of array is",largest_no(arr,n))
```


```python
Q82. Write a python programm to  cumulative sum of list ?
Ans-82. 
def cumulative(list):
    cum_list = []
    length = len(list)
    cum_list = [sum(list0:x:1)for i in range(0,length+1) return cum_list(1:)]
cum_list = [10,20,30,40,50]
print(cumulative(list))
```


```python
Q83. Write a python programm to check if a string is palindrome or not ?
Ans-83. 
num = input("Enter a number here : ")
temp = num
reverse = 0
while (temp>0):
    remainder = temp%10
    reverse = (temp*10)+remainder
    temp = temp//2
if num = reverse:
    print("Palindrome")
else:
    print("Not a Palindrome")
```


```python
Q84. Write a python programm to remove ith element from the string ?
Ans-84.
def remove_ith_element(n):
    str1 = "My name is mallishka"
     str2 = ""
        for i in range(len(str1)):
            if n ==i:
                continue
            else:
                str2 =str2+str1[n]
                return str2
        remove_ith_element(5)    
```


```python
Q85. Write a python program to check if a substring present in a given string ?
Ans-85. 
str1 = "She is my mother"
if mother in str1:
    print("Yes! it is present in string")
else:
    print("No! it is not present in string")    
```


```python
Q86. Write a python programm to find words greater than given length K ?
Ans-86. 
str = "Hello geeks for geeks"
k =4
x =str.splits(" ")
l = list(filter(lambda x : len(x)>k):s)
print(l)
```


```python
Q87 Write a python programm to extract unrequire dictionary values ?
Ans-87 
dict2 ={"iNeuron" : [1,2,4,9]
       "is": [3,7,9,0]
       "best" : [5,2,8,7]
       "for" : [3,9,7,5]
       "all student" : [1,8,3,4,8]
       }
print("The Original dictionary : "+str(dict2))
res = (list(sorted({ele for val in dict2.vaues() for ele in val})))
print("The unique values list is : "+str(res))
```


```python
Q88. Write a python programm to  merge two dictionary ?
Ans-88. 
dict1 = {"a" : 21, "b" : 34}, 
dict2 = {"c" : 50, "d" : 40}
print(Merge(dict1,dict2))
print(dict2)
```


```python
Q89. Write a python programm to convert list of tuple into dictionary ?
       input =[(Sachin,10),(MSD,7),(Kohli,18),(Rohit,45)]
       output={('Sachin' : 10),('MSD' : 7), ('Kohli' : 18),('Rohit' : 45)} 
Ans-89. 
print(dict([('Sachin' : 10), ('MSD' : 7),('Kohli': 18),('Rohit' : 45)]))
```


```python
Q90. Write a python programm to create a list of tuple from the given list having number and its cube in each tuple ?
       Input : list =[9,5,6] 
       Output : = [(9,729),(5, 125),(6,216)]
Ans-90.
     list1 = [9,5,6]
    res = [(val,pow(val,3))for val in list1]
    print(res)
```


```python
Q91. Write a python programm to get all combination of two tuple 
      Input : test_tup1 = (7,2),test_tup2 = (7,8)
      Output : [(7,7),(7,8),(2,7),(2,8),(7,7),(7,2),(8,7),(8,2)]
Ans-91. 
test_tup1 = (7,2)
test_tup2 = (7,8)
res = [(a,b) for a in test_tup1 for b in test_tup2]
res = res+ [(a,b) for a in test_tup2 for b in test_tup1]
print("The filtered tuple : ", str(res))        
```


```python
Q92. Write a python program to sort a list of tuple by second items 
      Input : [('452',10),('256',5),('100',20),('135',15)]
      Output : [('256',5),('452',10),('135',15),('100',20)]
Ans-92. 
def sort_Tuple(tup):
    lst = len(tup)
    for i in range(0,lst):
        
        for j in range(0,lst-i-1):
            if tup[j][1]>tup[j+1][1]:
                temp = tup[j]
                tup[j] = tup[j+1][1]
                temp = tup[j+1][1]
                
            return tup
        tup = [('452',10),('256',5),('100',20),('135',15)]
        print(sort_Tuple(tup))       
```


```python
Q93. Wrrite a python programm to print below pattern

 *
 ***
 ****
 *****
Ans-93. 
def myfunc(n):
    for i in range (0,n):
        for j in range(0,i+1):
            print('*',ends='**')
            print('\r')
          
        n=5
myfunc(n)   
```


```python
Q94. Write a python programm to print the below pattern:
         *
        **
       ***
      ****
      ****
Ans-94. 
def myfunc(n):
    k = n-1
    for i in range(0,n):
        for j in range(0,k):
            print('*',end = "**")
            k = k-1
        for j in range(0,i+1):
            print('*', ends = '**')
            print('\r')
    n = 5
    myfunc(n)
```


```python
Q95. Write a python program to print below pattern
              *
             **
            ***
           ****
          *****
```


```python
Q96. Write apython programm to print below pattern:
1,2
1,2,3
1,2,3,4
1,2,3,4,5
Ans-96. 
def myfunc(n):
    num = 1
    
    for i in range(0,n):
        num = 1
        for j in range(0,i+1):
            print(num,end = '')
            num = num+1
            print('\r')
          
        n = 5
        myfunc(n)
```


```python
Q97. Write a python programm to print below pattern:
    A
    BB
    CCC
    DDDD
    EEEEE
Ans-97. 
def alphabet(n):
    num = 65
    
    for i in range(0,n):
        num = 65
        
        for j in range(0,i+1):
            ch = ch(num)
            print(ch,end='')
            num =num+1
            print('\r')
            
        n = 5
        alphabet(n)
```


```python
Q98. Write a code to get a desired output of the following
string = "Big Data iNeuron"
desired_output = "iNeuron"

Ans-98. string[9:16]
```


```python
Q99. How can we acess element in a list?
Ans-99.we can acess by using indexing.
```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
