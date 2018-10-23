# A function to compute 5/0 and used try/except to catch the exceptions.

# 3.1
def divsn():
    try:
        a = int(input("Please enter an integer: "))
        b = int(input("Please enter an integer: "))
        val = int(a/b)
        print("Result =", val)
    except:
        print("Can't divide any number with zero value")
        
        
        divsn()
