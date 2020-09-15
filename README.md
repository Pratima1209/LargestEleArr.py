# LargestElementArr.py

# Python Program to find largest element in an array

arr=[1,2,3,5,60,120] 
n=len(arr)

def _max(arr,n):
    max=arr[0]
    for i in range(1,n):
        if arr[i]>max:
            max=arr[i]
    return max
ans=_max(arr,n)
print("Largest Element of Array = {0} is {1}".format(arr,ans))
