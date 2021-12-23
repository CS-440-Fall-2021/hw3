# Feedback Fall 2020


Learned
--

Raytracing
- understand the logic and maths behind the various ideas and their thorough implementation.
- Building a raytracer engine, thank you Kevin Suffern.
- Intersection of planes, spheres and triangles with ray and then the shading as well.
- how all different components of ray tracing are used together to display an image/scene.
- concepts of raytracing, how to set a viewplane, camera, ray and then direct that ray to the scene. How different objects interact with the ray, how to find hitpoint etc
- Ray + Primitive Interaction
- Sampling
- Shading
- Materials
- Fundamental understanding of how ray tracing really works.
- how each individual component comes together to form a scene
- how different parallel and perspective views are involved in raytracing

C++
- Building a raytracer engine, thank you Kevin Suffern.
- refreshed my c++ as well
- the use of 'default' in C++, which I did not think existed.
- implementation of ray tracing
- revision of OOP
- Pointers.
- Default Constructors.

Collaboration
- buddies are the material that infinitely reflect light on one another.

Improve
--

Code
- The given code could have been better explained because the transition and regulation between functions was really hard to keep track of.
- there were a lot of files that made debugging very difficult but the given structure was useful
- some more context as to where the given methods are going to be used would make it slightly easier for us to code.
- A demo ray tracer where we can understand or get help from with regards to the code.
- We should have a recitation devoted to bug checking. it is really hard to find small errors if your code manages to compile but still does not work.
- Appreciated the skeleton code.
- there was some confusion around what exactly the functions require at first, some details in the document would have been more helpful


All good
- There isn't much to improve in the homework. 
- It is perfect <3
- The homework was interesting to do.
- A lot of classes to handle but good practice.
- the homework was fun to do.

Coverage
- covering the related material before releasing the assignment

More
- Requiring basic acceleration techniques in submission such as uniform grid.
- Provide make files that let us build the code with a single
- Could have been shorter if were provided some premade classes. Most of the coding was repetitive.
- add more geometric types of primitives like different and complex shapes.

Other
- A little more time
- More detailed instructions are required. 
- By giving more clear instructions as to which functions exactly need to be implemented
- some more compiling instructions would have been really helpful.
- A more detailed and interactive description for the Ray Tracer could have helped more.
- A sample output file should have been given so as to compare the output.
- A guide to about we should go implementing the files rather than just giving header files.

Other
--

- This assignment helped me to understand the overall bare-bones structure of a ray-tracer without any complexity involved in any of the parts. Also, it helped me to identify the parts where the complexity or the working of the ray tracer could be made more better for visual quality - for e.g. the get_rays function in the simple class, the camera classes could be further added and modified, the hit_objects function in the World class. All in all, this was a really interesting and good hands-on assignment for learning ray-tracer structure.
- suffers from the curse known as End of the semester syndrome
- I had this one confusion after completing this assignment. We have not used get_BBox of Geometry class anywhere. In the hit_objects function of the World class, we are checking if the ray intersects with any of the geometry using their hit function. Then what exactly is the use case of get_BBox? Will we be using it once we implement acceleration structures and need to do intersection tests (this is what I believe as of now)? Or is there some other aspect to those?
