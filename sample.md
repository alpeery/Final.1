# Here are a few codes I wrote

### Project 1
```Python
print("Alexander Cowan")
print("I am a third year here at mizzou")
print("I'm excited to learn more about coding in python")
print("I am a very musically inclined as well")
```
### Project 2
```Python

import turtle

painter = turtle.Turtle()

painter.pencolor("purple")

for i in range(60):
    painter.forward(60)
    painter.right(150)

painter.pencolor("red")

for i in range(70):
    painter.forward(70)
    painter.right(160)

turtle.done()
```

### Project 3
```Python

print("This program calculates an object's final position. \n")

while (True):
        try:
                initial_position = float(input("Enter the object's initial position: "))
        except ValueError:
                print( "Only input numerical values please.")
        else:
                break

while (True):
        try:
                initial_velocity = float(input("Enter the object's initial velocity: "))
        except ValueError:
                print( "Only input numerical values please.")
        else:
                break

while (True):
        try:
                acceleration = float(input("Enter the object's acceleration: "))
        except ValueError:
                print("Only input numerical values please.")
        else:
                break

while (True):
        try:
                time_elapsed = float(input("Lastly enter the object's time elapsed: "))
                if (time_elapsed < 0):
                        print("Negative elapsed times are banned.")
                        continue
        except ValueError:
                print("Sorry, the value you used is not allowed, Only numerical values please.")
        else:
                break

final_position = initial_position + initial_velocity * time_elapsed + 0.5 *acceleration * time_elapsed ** 2

print("The object's final position is", final_position)

do_calculation = True
while (do_calculation):
        another_calculation = input("Do you want to operform another calculation? (y/n): ")
        if (another_calculation != "y"):
                do_calculation = false
```
