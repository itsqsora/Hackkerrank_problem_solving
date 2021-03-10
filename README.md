# Hackkerrank_problem_solving
# Min-Max Sum
#!/bin/python3

import math
import os
import random
import re
import sys

# Complete the miniMaxSum function below.
# โจทย์ข้อนี้ ผมจะเขียนให้ดูทั้งสองวิธี 
def miniMaxSum(arr):            
    '''
    s = 0
    minnum = 99999999999
    maxnum = 0
    n = len(arr)
    for i in range(n):
        s += arr[i]
        minnum = min(minnum, arr[i])
        maxnum = max(maxnum, arr[i])
    print(s-maxnum, s-minnum)
    '''
    print(sum(arr)-max(arr),sum(arr)-min(arr))

if __name__ == '__main__':
    arr = list(map(int, input().rstrip().split()))

    miniMaxSum(arr)
