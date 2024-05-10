# calculate_shape_area

def calculate_area(base, height, shape=""):
if shape == "triangle":
area = 1/2 _ (base _ height)
elif shape == "rectangle":
area = base \* height
else:
print("Error: Input shape is neither triangle nor rectangle.")
area = None
return area

base = 5
height = 10
print(calculate_area(base, height, "triangle"))
