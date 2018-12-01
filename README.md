This ray tracer that simulates refraction (with Schlick's polynomial approximation), metallic and Lambertain reflection, using spheres.

To use clone the respository and run g++ ppm.cpp -o exec. The scene can be varied by altering the randomScene function - number of spheres and material properties. Note: this implementation includes no optimzation and can take a while to run for complex scenes like in the sample image.
