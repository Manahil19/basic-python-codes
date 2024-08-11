# basic-python-codes
#1
var="this is python programming"
x=var.isupper()
print(x)

#2
var="this is python programming"
x=var.upper()
print(x)
print(x.lower())

#3
txt = "banana"
x = txt.center(20)
print(x)

#4
txt = "banana"
x = txt.rjust(20)
print(x, "is my favorite fruit.")

#5
a= "String"
for ch in a:
    print(ch,end="   $   ")

#6
from tkinter import*
window=Tk()
window.title("Hello")
window.mainloop()
