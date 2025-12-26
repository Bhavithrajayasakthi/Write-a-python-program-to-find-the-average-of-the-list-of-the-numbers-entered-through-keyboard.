# Write-a-python-program-to-find-the-average-of-the-list-of-the-numbers-entered-through-keyboard.
n=int(input("enter the limit "))
s=0
for i in range(1,n+1):
    print("enter",i, end='')
    a=int(input("th number:"))Write a python program to find the average of the list of the numbers entered through
keyboard.
    s=s+a
avg=s/n
print("the sum of entered numbers:",s)
print("the average of entered numbers:",avg)

output:
enter the limit 4
enter 1th number:3
enter 2th number:5
enter 3th number:7
enter 4th number:8
the sum of entered numbers: 23
the average of entered numbers: 5.75
