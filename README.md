# CS 3451 - Computer Graphics (Fall 2024)
![image](https://github.com/user-attachments/assets/aad015c1-2db7-4d3f-ab63-40788064b0a3)
## Overview:
##### Computer Graphics offers a comprehensive introduction to the mathematical and programmatic foundations of computer graphics. The course covers a range of topics, including the mathematical foundations, GPU pipeline, shape representation, procedural modeling, physically-based simulation, character animation, shading, lighting, texturing, and realistic ray-tracing rendering. The coursework encompasses a blend of programming assignments, in-class quizzes, a mid-term project, and a final project. These projects involve developing an interactive application using OpenGL and a modern GPU rendering pipeline to create visually impressive images and animations. 
##### Instructor: Bo Zhu
## Project Description:
##### In the final project, you are tasked with utilizing the graphic techniques learned in this class to interpret the theme ‘Journey.’ This open-ended assignment offers considerable freedom in implementing technical details, including mesh models, scene layout, materials, textures, lighting, animation, and GLSL shaders, to achieve a compelling graphical representation of the theme. 
##### Let this project be a journey in itself, where you utilize your skills with triangles, rays, matrices, shader functions, and imagination to interpret the theme of the journey. This is an opportunity to meld graphics techniques with your creative thoughts to develop visual narratives and personal expeditions that resonate with the beauty of this world.
## Aspects:
- ##### Artistic Contribution: The rendered image should exhibit complexity and visual appeal, demonstrating an advanced understanding of artistic principles in computer graphics. You are expected to integrate elements such as geometries, textures, materials, lighting, and noise to construct a scene that faithfully represents the chosen theme and stands out for its aesthetic quality.
- ##### Technical Contribution: Each team member contributes by developing and implementing at least one technical algorithm that is beyond the scope of our previous assignments. This algorithm should enhance the visual outcome of your project. It can pertain to any area of computer graphics, including but not limited to modeling, lighting, texturing, animation, and ray tracing. You may choose to extend the same algorithm (e.g., ray tracing or particle system), but you must show at least one new aspect of it in our final project. Potential areas of focus include but are not limited to the procedural modeling of intricate objects (e.g., grass and trees), new noise generation functions (other than Perlin noise), and the implementation of complex environmental effects such as skyboxes/spheres, bump/displacement/environmental mapping, procedural models, and advanced ray-tracing techniques (e.g., transparency, motion blur, participating media), etc.
##### In summary, your final project should blend aesthetic feeling and technical depth, showcasing your ability to create visually stunning graphics and your skill in applying advanced GLSL shader techniques to achieve these effects.
## Journey - A Reason to Love this World:
![image](https://github.com/user-attachments/assets/d148863b-e9b3-4593-8c82-30c92b3e2f44)
![image](https://github.com/user-attachments/assets/17d6817a-24d1-4326-afd1-880fe347f5b5)
##### My project is about a ship encountering big waves under a sky filled with stars and moonlight. I used to love the ocean when I was little, but as I have grown older, I feel both amazed and afraid of what might lie beneath the calm waves. Maybe there is a big shark, a water monster, or perhaps it is just my own fears lurking beneath the surface. I want to use this scene to represent a part of my life journey. I have faced many difficulties in life, but after every big wave, the sun always rises again. Even though I am afraid of what lies in the water, wherever I go, the moon and stars will always be by my side. I want to thank everyone who has been there for me and supported me, just like the stars and moon that guide and follow me.
## Technical Implementation:
1.	Background: a programmable canvas background option. 
2.	Moon: used the sky sphere to create the moon. 
3.	Ship: used a similar method as the moon to create the ship.
4.	Waves: used noise terrain to create waves.
5.	Clouds: used alpha blending to create the clouds.
---
##### Geometry: Simple geometric shapes such as spheres and planes were used.
##### Lightning: There are three light sources with Phong-based parameters (ambient, diffuse, specular)
##### Material: For the basic implementation, materials for objects were defined using Ka, Kd, Ks, and Shininess. For the advanced implementation, normal mapping was employed to showcase advanced surface details.
##### Texture: For the basic implementation, textures were loaded from images. For the advanced implementation, the waves were created using Perlin noise.
##### Background: A constant color.
