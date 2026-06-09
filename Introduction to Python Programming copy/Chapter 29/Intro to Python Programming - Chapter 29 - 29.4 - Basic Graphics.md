**Creating a Graphics Frame**
- A **graphical application** is a program that displays drawings and other graphical objects. TKinter displays contents inside a window called a **frame** using a Frame object
	- **Set the frame's size** by calling the geometry() method with arguments for the width and height
	- **Set the frame's title** by calling the title() method with a String as the argument
	- **Make the frame visible** to the user by calling the mainloop() method

**Drawing Graphical Objects**
- A **Canvas** is a graphical component that a programmer can use to draw basic shapes
1. **Arguments 1 and 2** - Coordinate for the top left corner (x0, y0) of the rectangle
2. **Arguments 3 and 4** - Coordinate for the bottom right corner (x1, y1)
3. **Argument 5 (optional)** - Rectangle outline color (if not set, the outline will be black)
4. **Argument 6 (optional)** - Rectangle fill color


| Shape     | Description                     |
| --------- | ------------------------------- |
| Rectangle | Draws a rectangle on the canvas |
| Oval      | Draws an ellipse on the canvas  |
| Line      | Draws a line on the canvas      |
| Polygon   | Draws a polygon on the canvas   |
