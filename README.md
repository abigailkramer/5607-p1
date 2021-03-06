# 5607-p1

## Project Difficulties
One of the difficulties I encountered was with the scaling of the square. My initial attempt 
at this involved the ratio between the distance from the center of the square to one of the 
points, and the distance from the center of the square to where the mouse's current position. This 
proved to be quite inefficient, with the visual scaling being jumpy and inaccurate. I changed the 
calculation to the ratio between the distance from the center of the square to where the mouse 
was clicked, and the distance from the center of the square to where the mouse's current position. 
This was a lot faster and smoother, and made more sense logistically. The last difficulty had to 
do with loading the image from a .ppm file. Initially, I read in the rgb values from the .ppm file 
in the "normal" order. Building the solution with this approach resulted in the image being loaded 
upside down. The natural solution was to just fill the .ppm file contents "upside-down" into the 
img_data array. After referring to the textbook reading on coordinate systems, and how the OpenGL 
coordinate system worked in this left-to-right, bottom-to-top order.

### Extra Features Added

- Changing something visually when the user	presses	the	keyboard
    - Rotate shape by 45 degrees clockwise when the 't' key is pressed
    - Rotate shape by 45 degrees counter-clockwise when the 'g' key is pressed

