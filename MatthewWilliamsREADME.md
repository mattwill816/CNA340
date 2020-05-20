# 4.12 LAB: Smallest number

Write a program whose inputs are three integers, and whose output is the smallest of the three values. Ex: If the input is: 7, 15, 3 and the output is: 3

## Getting Started
These instructions will install Pycharm on your local machine.

### Prerequisites
Python requires Pycharm to run, with no additional requirements.
[Pycharm](https://www.jetbrains.com/pycharm/download/#section=windows) 

## Running
Once installed you can run the program and copy and paste the code. 

**4.12 LAB: Smallest number**
Copy code below and enter it into Pycharm
```
if __name__ == '__main__':
    num1 = int(input())
    num2 = int(input())
    num3 = int(input())
    largest = num1
    if num2 < largest:
        largest = num2
    if num3 < largest:
        largest = num3
print(largest)

```
**Input**
```
7
15
3
```
**Output**
```
3

```


## Thanks
