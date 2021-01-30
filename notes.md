**Basics of python**
* : makes a new copy of the object.
```js
>>> 15 /2.5
6.0
>>> _
6.0
>>> _ /3.4
1.7647058823529411
>>> 
```
```js
a =[1,2,4]
a[-1]
print(a[-1]) //returns last element of the array 
```
* Tuples are immutable sequences 
* S= "krish"
* S=[0:3]
* ids = set([1,2,3,4])
* we can add and remove elements in set using .pop() and .add()
* Consider again sets x={1,2,3} and y={2,3,4}. How could you get {1, 4} from x and y using the provided set methods?
* (x| y) - (x & y)
**Dictionaries**
* Python dictionaries and the key-value pairs they contain dictionaries are mutable.
* age["Tim"]=age["Tim"]+1

```js 
>>> for x in range(10):
...     print(x)
... 
```
* List comphrehension 
```js
>>> numbers = range(10)
>>> sqaures = []
>>> for number in numbers:
...     square =number**2
...     sqaures.append(square)
... 
>>> 
>>> sqaures
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
>>> 
```
* How can you use a list comprehension, including if and for, to sum the odd numbers from 0 through 9? 
`sum([i for i in range(10) if i%2 == 1]).`
```js
krishnadevz@krishnadevz:~$ cat filename.txt
krishnadevz@krishnadevz:~$ nano filename.txt
krishnadevz@krishnadevz:~$ cat filename.txt
```
```js
>>> filename="filename.txt"
>>> for line in open(filename):
...     print(line)
... 
hello bro how you doing ?????

>>> 
```
**Functions**
```js
>>> def add(a,b):
...     mysum = a+b
...     return mysum 
... 
>>> 
>>> add(2,55)
57
>>> 

```
```js
 def password(length):
...     pw=str()
...     characters ="abcdef"
...     for i in range(length):
...             pw = pw+random.choice(characters)
...     return pw
... 
>>> password(3)
```
* `letter in 'aeiouy'` for check vowel we can use this 


