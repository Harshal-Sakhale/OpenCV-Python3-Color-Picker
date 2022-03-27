# OpenCV-Python3-Color-Picker
Click using mouse over an image to display color metrics of the pixel under the cursor

- Filename of the given image must be provided as the first argument on the command line. Otherwise a randomly generated gradient image is displayed. Each time a new image appears as it is randomly generated at runtime.

- First the user must click on the image where the color metrics are to be discoverd to select a ROI. However a single click is enough as there is no need to draw a rectangle. Rectangle is drawn automatically around the selected point where left mouse click occurs.

- Second the user must click in the middle section at a point whose color components are to be viewed.

- There are 3 sections of the window. 
   The rightmost is where the scaled down copy of the given image is displayed.
   The middle section is where a small region of the image is displayed full scale.
   The right most is where the chosen color is displayed along with the RGBA component values in decimal and hexadecimal.
