# task-21.8.2
from rectangle import Restangle,square, circle
rect_1 = Restangle(3,4)
rect_2 = Restangle(12,5)

print(rect_1.get_area())
print(rect_2.get_area())

square_1 = Square(5)
square_2 = Square(10)

circle = circle(pi,10)

print(square_1.get_area(),square_2.get_area(),circle)
figures = [rect_1, rect_2, square_1 ,square_2,circle]
for figure in figures:
    if isinstance(figure,Square):
        print(figure.get_area_square())
    else:
        print(figure.get_area())
elif isinstance(figure,circle):
print(f":{round(figure . get_area_circle(),2)}")
