# limit, diff, integrate
from sympy import *
x = Symbol('x')
y = Symbol('y')

print(limit(sin(x)/x, x, 0))
print(limit(sin(x)/x, x, -oo))

print(diff(sin(x)/x, x))
print(diff((x**2+x*y+3*x), y))
print(diff(x*cos(x), x, 3))


def partialDiff(function, tupleDiffSeq):
    """high order partial differential"""
    diffResult = function
    for diffSeq in tupleDiffSeq:
        diffResult = diff(diffResult, diffSeq)
    return diffResult


print(partialDiff(x*log(y)+x**2-y, (x, y)))

