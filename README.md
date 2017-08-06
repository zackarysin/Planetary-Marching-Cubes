# Planetary-Marching-Cubes
Developed originally for HelloPlanet

Planetary Marching Cubes (PMC) is an algorithm that allows the geneartion of a smooth sophisticaed planet mesh.

When I am still an undergrad student, I have decided that my final year project would be a planet simulating game that could simulate a planet to best of details for a game. Terrain is one of the key impactor to the simulation. River stems from mountain, plateau may have a lower temperature and caves is where some animals like bats sleeps. Very soon, I started to look into the method common for generating a planet. It seems that previous methods for generating planetary mesh mainly involves using a heightmap. 

![alt text](https://img.itch.zone/aW1hZ2UvNTIyNDUvMjU5ODc4LmpwZw==/original/UNVAN5.jpg)

Although visually pleasant, the method do not permits the planet to contains features such as caves and cliffhangs. So, I look further in games like ECO. ECO uses a voxel engine to implement a minecraft-like planet. It also looks very pleasant and allows the features such as caves and overhangs. But, the lack of smooth surfaces disturbs a perfectionists like me XD.

![alt text](http://www.strangeloopgames.com/wp-content/uploads/2015/08/World3-1024x576.png)

Using marching cubes is a good way to generate a mesh with smooth surface and complex features. However, if it is directly used for generating a planet, there will be sampling issues.

So, when I work on my FYP which I name HelloPlanet, I have taken a bit of time investigating on how to write an algorithm that could generate smooth planetary mesh with complex features like caves and overhangs. The result is what I call as Planetary Marching Cubes, you can see from the result below:

A paper has been written for PMC and will be submitted soon. You will be able find the details there! Likewise, the code will be released soon as well.

You can give HelloPlanet, and therefore PMC a try, by downloading HelloPlanet's EXE (64bits windows only) below:

Normal Version: https://drive.google.com/open?id=0B9fZr1uee_a3dllrdC1rVy1QaUk
VR Version:
