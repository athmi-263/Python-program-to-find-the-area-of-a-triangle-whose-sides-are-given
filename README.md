# Python-program-to-find-the-area-of-a-triangle-whose-sides-are-given
import math

a=float(input("Enter the length of side a :"))
b=float(input("Enter the length of side b :"))
c=float(input("Enter the length of side c:"))
s=(a+b+c)+2
area = math.sqrt(s*(s-a)*(s-b)*(s-c))
print("Area of the triangles is :",area)

Output:
Enter the length of side a :4
Enter the length of side b :5
Enter the length of side c:3
Area of the triangles is : 117.7285012220915
