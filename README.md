#### Diffusion Limited Aggregation


![Principals](./doc/Presentation/00.jpg)


Diffusion Limited Aggregation is a project that explores the application of morphogenetic algorithms to generate complex systems. The aim of the project is to understand and control the algorithm in order to generate a structure that can be translated into a constructive system.

The DLA is a theoretical growth that describes the clustering of particles through a diffusion process.  
Diffusion: the particles that form the structure wander around randomly before attaching to the system.
Limited: The wonder particles are considered to be in low concentrations so they don’t collide with each other before they become part of the growing system.
Aggregation: when the particles achieve a certain distance (aggregation distance) from one of the growth components they get attached to it.The first experiments consist of various simulations of 2D growth to understand the parameters that affect the DLA: Number of Seed, DLA Aggregation Diameter, Attractor Point and Boundary

![Principals](./doc/Presentation/02.jpg)




The next set of explorations aims to build a system in 3D. The strategy followed consists of placing the attractor point in a different plane than the rest of the parameters that define the growth and varying them to find out which role they perform in the definition of the DLA.

![Principals](./doc/Presentation/03.jpg)




In order to gain control over the system field conditions are implemented in the definition:
Point Charge, generates an organized cantilever geometry until approximately 200 iterations. Once this amount of iterations are exceeded the attractor point gains relevance in the system and the particles stop to aggregating.
Spin Forces | Double Spin Forces. Spiral geometry
Growth towards each other: Generates a bridge structure
Multiple Curve Attractor: Controls the growth through the use of curves

![Principals](./doc/Presentation/04.jpg)




For the constructability of the branching system, a post-DLA script has been applied. The purpose of the script is to get ride of the two balance nodes by augmenting the number of connections in the nodes.

![Principals](./doc/Presentation/05.jpg)




Join definition. The first step to define the joint is the creation of node openings. The segment that connects with the attached particle is replaced with a two curvature connection. Using a tween curvature component, ramifications of these curvatures are created. Finally, an extrusion in the directions of the pavilion surface is performed. The next step would be to give thickness to the structure to get a constructive component.

![Principals](./doc/Presentation/06.jpg)




Applying the script to a DLA pavilion developed with spin forces proof to not work accurately. Some modifications to the post DLA can be done to try to improve the shape obtained. However, the best approach would be to generate a DLA growth that allows for an easier rationalization of the structure.

![Principals](./doc/Presentation/07.jpg)






#### Getting Started

The folder *src* contains one folder with the final files and anotherone that collects all of the different experimentations that took place during this research.

The folder *doc* contains: the images that appear in this post, *Presentation*; images of the different experiments, *images* and *videos*


#### Requirements

Rhino 5 or 6
Grasshopper
Plugins: Galapagos | Kangaroo2 | Anemone | 


#### References

http://paulbourke.net/fractals/dla/ 
http://toxiclibs.org/2010/02/new-package-simutils/ 
https://issuu.com/ale2x72/docs/dendritic_laminar_assemblies 


#### Credits

*Diffusion Limited Aggregation* is a project of IaaC, Institute for Advanced Architecture of Catalonia developed in the *Masters of Robotics and Advanced Construction* in 2019/20 by Students: *Abdullah Sheikh, Andreea Bunica, Anna Batalle Garcia* Faculty: *Alessio Alessio Erioli, Eugenio Bettucchi*
![Principals](./doc/Presentation/05.jpg)



