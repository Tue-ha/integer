import math

def count_common_multiples(a, b, c):
    lcm = abs(a * b) // math.gcd(a, b)
    count = c // lcm
    return count
    
