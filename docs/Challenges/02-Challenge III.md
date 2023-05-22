---
hide:
    - toc
---
# Challenge III: Digital Tiles
Caglar / Ahmed / Marc

A DIY ToolKit to design and build tiles through a process that combines physical interaction and digitalisation.

**"Playing in the physical and converting it to the digital"**

During the first challenge, we developed a project where we designed a tile decorating kit with a focus on digitalization to make it easy and meaningful. Our goal for the second Challenge was to convert it from 2D to 3D, which led us to explore 3D fabrication techniques.

For this third challenge we decided to continue the [first Challenge](https://github.com/paresmarc/tiledeco) and develop iterations to improve it and make it a more automated process with open-source softwares to improve the accessibility.

As a group we decided to develop an interface for our tile-deco and pixel-cube projects ( maybe a website) in order to eliminate the use of grasshopper apps and firefly plugin and make the process more accessible and easier if possible. Briefly, our main goal is to support the makers and crafts, and encourage them to use digital fabrication tools.

We agreed on using OPENCV shape detector. But, in order to use OPENCV we need PHYTON, ANACONDA and VISUAL STUDIO too. Firstly, we set the anaconda and phyton and opencv. Then we found a code for shape recognition-detection especially for “circle” from an image. We tested that through the anaconda and of course code had some problems and we asked from CHATGPT to fix the code. More or less the code works through the image but we needed to calibrate the parameters in order to get more accurate results.

During the second day we continued to work on shape detection code. After detecting the circles on the still images we tried to configure the code for squares, rectangle, triangle, semi/quarter circles. We used edge detection and tried to convert them to defined geometric shapes, but we had problems with some undefined ones as lemon shape or croissant shape. So, in order to solve this we worked on polygon contouring but it did not ended up with smooth curves. Then, Pietro joined to support us for using phyton libraries.

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/m1.png" width="32%" height="32%"/>
<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/m2.png" width="32%" height="32%"/>
<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/m3.png" width="32%" height="32%"/>


**Design Steps:**

1. Interactive physical modular system to create myriad shapes

2. Research around OpenCV, detection software of movement and rotation of shapes

3. How to digitalise perfect shapes in order to create a shape to be 3D printed

4. Build a DIY hydraulic press to fabricate tiles


Repo link Challenge III:

https://github.com/paresmarc/digitaltiles


## Reflections

Given that the project involved connecting the physical and digital, there were many details that needed to be solved. We decided to let people play, change, and combine shapes attached to a base-grid with magnets to build their unique design.

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/code.jpg" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/coins.gif" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/detect.gif" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/python.jpg" width="66%" height="66%"/>

We started with the digitalization process and thought carefully about how to convert physical items into digital representations. We started working and discovering how OpenCv works without any background in Python or coding. This process, even thought after two days of research we realised that was too difficult for one week project, was an interesting investment in order to learn the basics of Python and OpenCV.

We decided to stay with Grasshopper and Firefly because we already had a robust setup and dedicate more time improving the physical interaction and the DIY hydraulic press system.

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/cura.jpg" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/print.gif" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/mould.jpg" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/fidu.jpg" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/hydraul.gif" width="66%" height="66%"/>

<img src="https://paresmarc.github.io/MDEF/images/term3/ch3/final.jpg" width="66%" height="66%"/>
