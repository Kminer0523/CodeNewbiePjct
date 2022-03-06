# CodeNewbiePjct
My initial CN Project

$ git clone https://github.com/Kminer0523/CodeNewbiePjct
  
  
  import turtle
jenny = turtle.Turtle()
def some_shape(length, color, sides):
   
    for side in range(sides):
        jenny.color(color)
        jenny.forward(length)
        jenny.right(360 / sides)
  
    jenny.right(30)
    
    
some_shape(90, "red", 6)
  
some_shape(90, "orange", 6)
  
some_shape(90, "green", 6)

