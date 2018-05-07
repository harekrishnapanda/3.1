# 3.1
def divsn():
    try:
        a = int(input("Please enter an integer: "))
        b = int(input("Please enter an integer: "))
        val = int(a/b)
        print("Result =", val)
    except:
        print("Can't devide any number with zero value")
        
        
        divsn()
