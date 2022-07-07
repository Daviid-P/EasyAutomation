Mouse and keyboard automation functions for my own convenience.

To install:
`pip install easyautomation`

To use:
```python
from easyautomation import mouse, keyboard

# Move to the (x,y) coordinates (500,500) on the monitor
mouse.moveTo(x=500, y=500)

# Open Chrome
keyboard.win()
keyboard.instaWrite("chrome")
keyboard.enter()
keboard.maximizeWindow()
```

# Mouse methods
- moveTo(x, y, wiggle=True)
- moveToAndClick(x, y, wiggle=True, image=None, first=False)

# Keyboard Methods
- newTab()
- ctrlEnter()
- maximizeWindow()
- snapLeft()
- addressBar()
- selectAll()
- copy()
- paste()
- write(string)
- instaWrite(string)
- f12()
- enter()
- backspace()
- escape()
- space()
- win()
- left()
- right()
- up()
- down()


# Note:
I made this years ago, don't even remember why I did what I did and how I did it.

If I ever feel like it I'll update this to take a numpy array as an image input instead of a string to look for a filename in a folder.
