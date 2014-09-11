Class-Work
==========

Some of the class work so far!

from numpy import array, dot
a=[3, -4, 2]
b=[2, 1, -1.5]
a=array(a)
b=array(b)

# Attempted for loop. However I didn't get to finish it in class
# and haven't had the chance to play with it some more.

#magnitude_a=0
#length_a=len(a)
#for number in range(0,length_a):
#    magnitude_a=a[number]**2+magnitude_a 
            

magnitude_aprime=a[0]**2+a[1]**2+a[2]**2
magnitude_aprime=magnitude_aprime**.5
# magnitude_b=b[0]**2+b[1]**2+b[2]**2


print (dot(a,b))
print (magnitude_aprime)

# THis is the ball drop!

def ball_drop():
    height=float (input("What is the height?  "))
    t=(2*height)**.5/(9.8)**.5
    return ball_drop
    
total=ball_drop() 
print ("The total time it takes to fall is %f" %t)

