## 1. Find simple Reverse in string and have negative index ?
```phython

text = "Hello Baby"

reverseText = " "
for index in range(1, len(text) + 1):
    reverseText += text[-index]
print ( reverseText)

#ybaB olleH

```
## 2. Find simple Reverse in string that use (::-1) or reverse() ?
```phython
text = "Hello Baby"

lastIndex = len(text) - 1
reverseText = " "

for index in range(len(text) ):
    reverseText += text[lastIndex-index]
print(reverseText)

#ybaB olleH
```
## 3. Find add number in array by index
```phython

arr = [5, 7, 8, 4, 3]
indexOfOdd = []
for i in range(len(arr) ):
    if arr[i] % 2 == 1:
        indexOfOdd.append(i)
print(index0f0dd)

#Output: [0, 1, 4]
```
## 4. Find Average of number in array
```phython

arr = [5, 7, 8, 4, 3]
average = 0
sum = 0
for value in arr:
    sum += value # sum = sum + value
average = sum / len(arr)
print(average)

#Output: 5.4
```
## 5. Find name of dictionary
```python

arr = [
{'name' : 'bopha', 'age': 18},
{'name' : 'thida', 'age': 12},
{'name' : 'kanha', 'age': 16},
]
for dics in arr:
    print(dics[ 'name' ])

#bopha
#thida
#kanha
```
## 6. How many total in array ?
```phython

arr = [5, 7, 8, 4, 3]
sum = 0
for value in arr:
    sum += value # sum = sum + value
print(sum)

#Output: 27
```
## 7. Find Even number in array
```phython

arr = [5, 7, 8, 4, 3]
for value in arr:
    if value % 2 == 0:
        print(value)

#Output: 8 4
```
## 8. Find minimum in array 
```phython

arr = [10, 40, 20, 4, 3]
min = arr [0]
for value in arr:
    if value < min:
        min = value
print(min)

#Output: 3

```
## 9. Please move number one to right step 
```phython

arr = [0, 0, 1, 0, 0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i + 1] = 1
        isFound = True
print(arr)

#Output: [0, 0, 0, 1, 0]

```
## 10. Please move number one to left step
```phython

arr = [0, 0, 1, 0, 0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i - 1] = 1
        isFound = True
print(arr)

#Output: [0, 1, 0, 0, 0]
```
## 11. Find maximum in array 
```phython

arr = [10, 40, 20, 4, 3]
max = arr [0]
for value in arr:
    if value > max:
    max = value
print(max)

#Output: 40
```
## 12. Please Sum value in row
```phython
arr2D = [
[1, 2, 3],
[4, 5, 6],
[7,8, 9],
]

sum = 0
arr = []
for row in range(len(arr2D) ):
    for col in range(len(arr2D[row])):
        sum += arr2D[row] [col]
        arr.append(sum)
    sum = 0
print(arr)
```
