**Introduction to Matplotlib**
- **Matplotlib** is a package used to create static, dynamic, and interactive plots
- Figures can be created using the **pyplot** library, a state-based interface to the Matplotlib package that uses a syntax similar to MATLAB

| **Versatility**     | Can be used in Python scripts, shells, iPython, and Jupyter Notebooks |
| ------------------- | --------------------------------------------------------------------- |
| **Familiarity**     | Uses MATLAB-style functions                                           |
| **Portability**     | Runs on MacOS, Linux, and Windows                                     |
| **Customizability** | Can adjust details of a plot like axes, legends, and color            |

**Plotting with Matplotlib**
- The most common object is a line plot, created using the **plot()** function, which connects consecutive x- and y- coordinates. Another common object is a scatter plot, created using the **scatter()** function, which shows all pairs of x- and y- coordinates
	- **figure()** - Creates a new figure for a plot to appear in
	- **show()** - Displays the figure and all the objects the figure contains
	- **savefid("fname")** - Saves the figure in the current working directory with the filename here

**Labeling Plots**
- The pyplot **title()** function adds a title to a figure. The **xlabel()** and **ylabel()** functions add x- and y- axis labels to a plot
	- **text(x, y, s)** - Adds string s to the figure at coordinates (x, y)
	- **annotate(s, xy, xytext)** - Links string s at coordinates given by xytext to a point given by xy
	- **legend(loc)** - Adds a legend in the figure in a specified location (loc), which can include "best", "center", "upper center", "lower center", "center left", "center right", "upper left", "upper right", "lower left", and "lower right". If no loc is given, legend is placed at the "best" location with the least plot overlap.

**Styling Plots**

| Character(s) | Line Color/Style | Character(s) | Marker Style                    | Character(s) | Marker Style           |
| ------------ | ---------------- | ------------ | ------------------------------- | ------------ | ---------------------- |
| b            | Blue             | .            | Point marker                    | 1            | Tri-down marker        |
| g            | Green            | ,            | Pixel marker                    | 2            | Tri-up marker          |
| r            | Red              | O            | Circle marker                   | 3            | Tri-left marker        |
| w            | White            | +            | Plus marker                     | 4            | Tri-right marker       |
| k            | Black            | x or X       | Thin x marker or thick X marker | h            | Hexagon1 marker        |
| y            | Yellow           | v            | Triangle-down marker            | H            | Hexagon2 marker        |
| m            | Magenta          | ^            | Triangle-up marker              | D            | Diamond marker         |
| -            | Solid line       | <            | Triangle-left marker            | d            | Thin diamond marker    |
| :            | Dotted line      | >            | Triangle right-marker           | \|           | Vertical line marker   |
| --           | Dashed line      | *            | Star marker                     | _            | Horizontal line marker |
| -.           | Dashed-dot line  | p            | Pentagon marker                 | s            | Square marker          |

**Grid Lines**
- The pyplot **grid()** function adds grid lines to a plot

**Multiple Plots**
- Multiple plots can be drawn in the same figure using the pyplot **subplot()** function
- The pyplot function **suptitle()** adds a title to the entire figure, not just the individual subplots