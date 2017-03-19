Q1 Exercise 8.6, page 276, of the textbook (copied here): Write a program to draw the Mandelbrot 
set, and when clicked on the Mandelbrot image, a Julia set corresponding to the clicked point is drawn 
on a window aside of the Mandelbrot window (each Julia set in a different color). The clicked point in 
the form of z = x + yi should also be displayed on the side window. Call your program "mandeljulia.java" 
Q2 Adapt/modify the grammar generation program to generate a tree with branches of different 
thicknesses like the one shown below (hints: draw stacked horizontal lines with decreasing thickness 
going upward). 
Q3 Add green leaves to the branches and make the leaves oriented toward the same 
directions as the branches.

--------------- using jar file to run this project
using these following commands to run this project 
java -jar Q1.jar
java -jar Q2.jar
java -jar Q3.jar


---------------main entry of my code
all my java file is in the directory src/leo
Q1:   mandeljulia.java
Q2:   FractalGrammars.java
Q3:   FractalGrammarsAddLeaf.java


-----------using commandline to run this project
1. make sure to let 'src/' as current directory

2. compile using following command:
javac -cp . ./leo/*.java

3. run this project using following command:
java leo.mandeljulia
java leo.FractalGrammars
java leo.FractalGrammarsAddLeaf


 


