# Write-a-python-program-to-find-the-average-of-the-list-of-the-numbers-entered-through-keyboard.
n=int(input("Enter the limit"))
s=0
for i in range(1,n+1):
    print("Enter",i,end='')
    a=int(input("th number:"))
    s=s+a
avg=s/n
print("the sum of entered numbers:",s)
print("the average of entered numbers:",avg)

output:
Enter the limit 4
Enter 1th number:67
Enter 2th number:789
Enter 3th number:23
Enter 4th number:678
the sum of entered numbers: 1557
the average of entered numbers: 389.25
