# ComputerGraphics_Cpp_OpenGL
Computer graphics example code written in C++ using OpenGL

# Purpose
This code was written in CS-330, a computer graphics course focused on OpenGL, an industry standard for C++ graphics libraries.  This program renders a a few objects on a table top.  A screenshot is included below.

![CS-330_Screenshot](https://user-images.githubusercontent.com/31283921/221336913-85d96402-1c60-42c1-b334-e1d0bb2aebd9.jpg)

# Additional Libraries
All code in this repository was written by William Brandow.  Additional libraries required for the execution of this code are as follows:
 - GLFW (version 3.3.8) - glfw.org
 - GLEW (version 7.0) - glew.sourceforge.net
 - GLM - github.com/g-truc/glm
 - stb_image - github.com/nothings/stb
 
 # Lessons Learned
 This project involved more than getting good practice with C++ and some very useful graphics libraries.  This was a behind the scenes look at how programs like Blender and AutoCAD work.  Both of these are written using OpenGL.  Having this deeper understanding of these programs will make them much easier to learn. 
 This has also been important practice in creating modular code.  My Shape.cpp file can be reused on future projects to quickly create new scenes in a fraction of the time.  This skill is useful in all disciplines of software development, not just computer graphics.
 
 # Future Development
Work on this project is still ongoing.  I would like to spend more time texturing the objects and adding shadows in order to make the scene more realistic.  I would also like to add code to prevent the camera from passing through the objects.  After that I will likely stop adding to this scene and rather focus on refactoring the code to ensure I'm able to reuse as much as possible in future projects.  For example, I would like to move input processing functions into their own .cpp file.  
 
 
 
