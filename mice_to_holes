def assignHole(mices, holes, n, m):
    if (n != m):
        return -1
    # Sort the arrays
    mices.sort()
    holes.sort()
    Max = 0
    for i in range(n):
        if (Max < abs(mices[i] - holes[i])):
            Max = abs(mices[i] - holes[i])
    return Max
    
# Driver code

# Position of mouses
n= int(input())
mices = list(map(int,input().split()))
holes = list(map(int,input().split()))
# Number of mouses
n = len(mices)
# Number of holes
m = len(holes)
# The required answer is returned
# from the function
minTime = assignHole(mices, holes, n, m)
print(minTime)
