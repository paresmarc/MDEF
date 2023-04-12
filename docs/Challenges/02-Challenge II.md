---
hide:
    - toc
---
# Challenge II: Pixel Cubes
Caglar / Ahmed / Marc

Modular system to create 3D digital models through physical interaction.

**"Playing in the physical and converting it to the digital"**

During the first challenge, I participated in a project where we developed a tile decorating kit with a focus on digitalization to make it easy and meaningful. Our initial goal for the second Challenge was to convert it from 2D to 3D, which led us to explore 3D fabrication techniques.

To guide us in the project, we looked at reference projects like MIT's interactive shape-shifting table and Reactivision Improvisation with MIDI (Reactable). However, we had to simplify our goals due to the time constraints.

**Design Steps:**

1. Interactive physical modular system to create myriad volumes

2. Research around webcam detection software of movement and rotation of shapes

3. How to combine and assemble cubes in order to create volumes

4. Make the user interact with the Software. Incorporate Arduino

<img src="https://paresmarc.github.io/MDEF/images/term2/draft/cha2.png" width="100%" height="100%"/>

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFddcJntxw&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFddcJntxw&#x2F;view?utm_content=DAFddcJntxw&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Pixel Cubes</a> de Marc Parés

Repo link Challenge II:

https://github.com/paresmarc/pixelcubes


## Reflections

Given that the project involved connecting the physical and digital, there were many details that needed to be solved. We decided to let people play, change, and combine cubes attached to a base-grid with magnets to build their unique design rather than sticking to 2D geometric shapes.

We started with the digitalization process and thought carefully about how to convert physical items into digital representations. We discovered a system called "fiducial ID," which works like QR codes (but with more organic shapes) through cameras. Each cube on the grid had a unique "Fiducial ID," which gave it a parameter on the Z axis to help form a unique 3D design.

However, we encountered challenges with the camera detecting the fiducials repeatedly, which created a lot of trash on the system. We ended up resetting the system to solve this issue.

Besides the digitalization, we also worked on the physical object. Initially, we 3D printed the cubes, but it was not appropriate due to the long printing time. We ended up building the cubes out of wood and inserted the magnets on their surfaces using a magnet insert (nest) designed for each magnet. We also engraved the outlines and drew the fiducials by hand since vinyl did not stick properly to the wood.

Moreover, we had trouble cutting the cubes out of the oak block, which was 33 mm thick. We had to carve the surface 3mm to get 30mm thickness, and we did that with the help of Adai and Edu. We discovered the facing function of the RhinoCam-CNC, which provided the carving function with the end-mill having a 30mm diameter. To eliminate material loss in CNC, Adai and I cut the cubes manually with a saw, which required a lot of attention and physical effort.

We used the CNC machine to build the grid out of plywood and designed and laser-cut acrylic to build a structure to hold the camera above the grid. That structure could be located in different positions on the grid to capture the cubes clearly.

During the project, we mostly used the grasshopper for digitalization, but we also added the arduino to use the firefly plug-in and a button to capture the desired design and build it with the 3D printer.

While working on the project, I realized that the group nature of the challenge meant that most tasks had to be done by different colleagues, and each person ended up working on their area of expertise to use time efficiently. However, this resulted in a lack of opportunities to improve other skills, especially coding. I would have preferred more classes on coding, like the ones Oscar gave, to improve my coding skills. During each challenge, I was unable to improve my coding skills because, as a maker, I had to work on the machines and 3D modeling. Moreover, we didn't have much time to learn from my classmates.

To sum up, I did learn a lot from the project, but the intense nature of the challenge week did not allow me to discover or learn more coding skills from my colleagues or instructors. Thus, I have doubts about the efficiency of the challenges.

<img src="https://paresmarc.github.io/MDEF/images/term2/draft/cubes.png" width="100%" height="100%"/>

We tested the interaction and process during the Design Dialogues II

<img src="https://paresmarc.github.io/MDEF/images/term2/draft/desdi.jpg" width="100%" height="100%"/>

<img src="https://paresmarc.github.io/MDEF/images/term2/draft/pixeldial.jpg" width="75%" height="75%"/>
