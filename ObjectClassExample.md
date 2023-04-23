#class example

def __init__ (self, x, y):
self.x = x
self.y = y

c = coordinate (3,4)

origin = coordinate (0,0)
print(c.x)
print(origin.x)

def distance (self, other):
x_diff_sq = (self.x-other.x)**2
y_diff_sq = (self.y-other.y)**2
return (x_diff_sq + y_diff_sq)**0.5

#how to use a method
#def distance(self, other):
#code here
