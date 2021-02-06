## 5607 - Project 1 - Abigail Kramer


### Project Difficulties
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

### Pictures of Project in Process

![image](https://user-images.githubusercontent.com/59031606/107131532-fa645b80-689c-11eb-9b56-3959a5c72a9c.png)
![image](https://user-images.githubusercontent.com/59031606/107131576-529b5d80-689d-11eb-80b7-5b10f3f49dff.png)
![image](https://user-images.githubusercontent.com/59031606/107131588-68a91e00-689d-11eb-8674-0e1df91bb1ce.png)
![image](https://user-images.githubusercontent.com/59031606/107131600-7a8ac100-689d-11eb-8a8d-e3fa03ca8ed4.png)
![image](https://user-images.githubusercontent.com/59031606/107131612-95f5cc00-689d-11eb-8e48-2ce1091389de.png)
![image](https://user-images.githubusercontent.com/59031606/107131617-a7d76f00-689d-11eb-8371-28f683bcda13.png)

