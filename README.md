# ProjEuler15


import math


# to compute the solution we use binomial distribution  reflecting to the binomial model

def binomial(n, k):
    assert 0 <= k <= n
    return math.factorial(n) // (math.factorial(k) * math.factorial(n - k))

#We now know the size of the grid
print("welcome. First you need to know the horizontal length of the grid")
a = int(input())

print("now you need the vertical length")
b = int(input())

