# find-large-number
list=[1,2,3,4,5,1,10,15,24,5,8,45,47,51,25,145,124,458,12,475,10]
n=max(list)
print('The large number is:',n)

#2nd type
a=int(input('Enter a number:'))
b=int(input('Enter a number:'))
c=int(input('Enter a number:'))
if(a > b) or (a > c):
    print(a,'is larger number from all given')
elif(b > c) or (b > a):
    print(b,'is larger number from all given')

else:
    print(c,'is larger number')
