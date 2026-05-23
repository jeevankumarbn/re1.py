def avrg(*n):
    if len(n)==0:
        return 0
    return sum(n) / len(n)
print(avrg(10, 20, 30))
