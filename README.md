# seam-carving
The objective of this seam carving algorithm is to perform content aware resizing of images. This allows image to be resized without losing meaningful content from cropping or scaling

<img src="https://github.com/andrewdcampbell/seam-carving/blob/master/demos/visuals/lake_shrink.gif" width="900">

Princeton University CS project.

https://www.cs.princeton.edu/courses/archive/spring22/cos226/assignments/seam/specification.php
https://www.cs.princeton.edu/courses/archive/spring22/cos226/assignments/seam/checklist.php

---

### To run this program:
Clone the repository onto your computer: `$ git clone https://github.com/AliiaaT/seam_carving.git

Set up the algs4 library, from the link:
http://algs4.cs.princeton.edu/code/ .
On that page, there are instructions on how to set up the library. 

Once done with that, you will be able to compile java files in your local repo.

For example ResizeDemo.java:
```
/* *****************************************************************************
 *  Compilation:  javac-algs4 ResizeDemo.java
 *  Execution:    java-algs4 ResizeDemo input.png columnsToRemove rowsToRemove
 *  Dependencies: SeamCarver.java
 *                
 *
 *  Read image from file specified as command line argument. Use SeamCarver
 *  to remove number of rows and columns specified as command line arguments.
 *  Display the image and print time elapsed.
 *
 *  % java ResizeDemo HJoceanSmall.png 150 0
 *
 **************************************************************************** */
 ```

Closing the images ends the program.

---

# Output of the program
## Before HJocean.png.      
Removed 150 columns.

![Before](https://github.com/AliiaaT/seam_carving/blob/main/output/Before_HJocean.png)
## After HJocean.png
![After](https://github.com/AliiaaT/seam_carvings/blob/main/output/After_HJocean.png)

