# 3D Solar system
Delevoper: Daniel Milev <br>

<a href="https://github.com/antonmilev/Test2/raw/refs/heads/main/install/SolarSystem.zip">Download</a>
# Introduction

Goal: 3D Solar System simulation allows us to visually get acquainted with the planets, their volume, to get an idea of ​​how and how fast they move, how far they are from them and their size. <br> <br>
In the application, the speed of movement of the planets can be changed, while maintaining the correspondence between the speeds of the planets. You can stop at a moment of your choice, study their positions and start again, you can approach the planets or study them from afar. Different positions allow you to get an idea of ​​what it would be like if you were in the asteroid belt, or what the movement of planet Earth from the Moon, or Jupiter from Ganymede looks like.
Of course, everyone dreams of flying into space and I really hope that in the near future it will be possible... but until then, 3D Solar System gives you the opportunity to pilot a spaceship to the Sun or Pluto. <br> <br>
I wish you a pleasant journey....

<p align="center">
<img src="pics/start.jpg" width="854px"/>
</p>

# Main stages in the implementation of the project

- Defining an idea
- Presenting to the manager
- Determining technical means for development
- Planning and shaping the project
- Developing functionality
- Testing and correction
- Publishing and sharing

# Used technologies

- C++ -- Programming Language
- Microsoft Visual Studio - Programming Environment
- Assimp - assimp is a library that loads various 3D file formats.
- OpenGL - OpenGL is a cross-language, cross-platform application programming interface for rendering 2D and 3D vector graphics.
- GLFW - It provides a simple API for creating windows, contexts, and surfaces, receiving input, and events.
- Github - GitHub is a cloud-based platform where you can store, share, and collaborate with others to write code.
- Glm - C++ math libraries for OpenGL
- GLSL - is a high-level shading language designed for writing shaders
- FreeType2 - open-source software library designed for rendering fonts
- SketchUp - popular 3D modeling software used for creating, editing, and sharing 3D design

# Logical and functional description of the application

The program allows you to view different viewpoints and moons, change cameras and various other changes with these buttons, you can remove or add orbits, launch a special mode for additional information, etc.

### Keyboard
- WASD and arrows – camera movement
- 1 – 0 on the keyboard – change camera to planets view
- 1 – 6 on the keypad  - change camera to moons view
- E – change background
- I – enter and exit a spaceship
- O – show orbits
- P – freeze time
- J – change camera to side view (in planet view)
- K – show spaceship
- L – change language
- Keypad (+, -) – change simulation speed
- Space – return to default POV
- F1 – change POV to freecam
- X - display additional info (in planet view)
- F - Toggle fullscreen

### Mouse
- left button - panning in X and Z axis
- scroll button - zoom in/out
- right button - rotate

Camera view can be moved with WASD (in X and Z axis) and Arrows for up and down (in Y axis).

<div align="center">
<video src="https://github.com/user-attachments/assets/93e99bb8-7f29-4a39-b89f-99a0e82a597e" />
</div>

Asteroid belt view is activated by pressing the 0 key:

<div align="center">
<video src="https://github.com/user-attachments/assets/b8a709a6-67bc-4fda-bf5d-5f1afc7a1ef3" />
</div>

Detailed info of asteroids can be activated with X key:

<div align="center">
<img src="pics/AsteroidsInfo.jpg" width="854px"/>
</div>

The display of planet orbits can be toggled on and off using the "O" key, and this feature works in both normal and planet views.

<p align="center">
<img src="pics/Orbits.jpg" width="854px"/>
</p>

You can switch between the following planetary camera views using the 1-9 keys on the keyboard:

| <img src="pics/Mercury.jpg" width="300px"/> |  <img src="pics/Venus.jpg" width="300px"/> | <img src="pics/Earth.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Mercury - Key:1 </b>* | *<b>Venus  - Key:2</b>* | *<b>Earth - Key:3</b>* | 

| <img src="pics/Mars.jpg" width="300px"/> | <img src="pics/Jupiter.jpg" width="300px"/>|<img src="pics/Saturn.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Mars - Key:4 </b>* | *<b>Jupiter - Key:5 </b>* | *<b>Saturn - Key:6 </b>* | 

| <img src="pics/Neptune.jpg" width="300px"/> | <img src="pics/Uranus.jpg" width="300px"/>|<img src="pics/Pluto.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Neptune - Key:7 </b>* | *<b>Uranus - Key:8 </b>* | *<b>Pluto - Key:9 </b>* | 

Planets and moons view can be switched to side orbital view with J key:

| <img src="pics/Mercury2.jpg" width="300px"/> |  <img src="pics/Venus2.jpg" width="300px"/> | <img src="pics/Earth2.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Mercury Side View - Key:1+J </b>* | *<b>Venus Side View - Key:2+J</b>* | *<b>Earth  Side View- Key:3+J</b>* | 

| <img src="pics/Mars2.jpg" width="300px"/> | <img src="pics/Jupiter2.jpg" width="300px"/>|<img src="pics/Saturn2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Mars Side View - Key:4+J </b>* | *<b>Jupiter Side View- Key:5+J </b>* | *<b>Saturn Side View - Key:6+J </b>* | 

| <img src="pics/Neptune2.jpg" width="300px"/> | <img src="pics/Uranus2.jpg" width="300px"/>|<img src="pics/Pluto2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Neptune Side View - Key:7+J </b>* | *<b>Uranus Side View - Key:8+J </b>* | *<b>Pluto Side View - Key:9 +J</b>* | 

Camera views for several of the moons (1–6 on the keypad):

| <img src="pics/Moon2.jpg" width="300px"/> |  <img src="pics/Io2.jpg" width="300px"/> | <img src="pics/Europa2.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Moon - KeyPad:1</b>* | *<b>Io - KeyPad:2</b>* | *<b>Europa- KeyPad:3</b>* | 

| <img src="pics/Ganymede2.jpg" width="300px"/> | <img src="pics/Callisto2.jpg" width="300px"/>|<img src="pics/Triton.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Ganymede - KeyPad:4 </b>* | *<b>Callisto- KeyPad:5 </b>* | *<b>Triton - KeyPad:6 </b>* | 

In planet views there is additional information about the planets displayed with X key:

| <img src="pics/EarthInfo.jpg" width="300px"/> |  <img src="pics/MarsInfo.jpg" width="300px"/> | <img src="pics/PlutoInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Earth - Key:3+X</b>* | *<b>Mars - Key:4+X</b>* | *<b>Pluto- Key:9+X</b>* | 

Again J and O keys can be used to display planet orbits:

<div align="center">
 <video src="https://github.com/user-attachments/assets/4a4b5588-219a-4aa4-bb61-bf4b96394c10" />
</div>

# More to come..
<ul>
  <li>Spacehip travel around the solar system </li>
  
  | <img src="pics/Spaceship1.jpg" width="300px"/> |  <img src="pics/Spaceship2.jpg" width="300px"/> | <img src="pics/Spaceship3.jpg" width="300px"/> 
  |:---:|:---:|:---:|
  <li>Selection of planets and interaction </li>
  <li>Showing planets internal structure</li>
</ul> 

# Drew inspiration from
* <a href="https://learnopengl.com">learnopengl</a> - extensive tutorial resource for learning OpenGL
* <a href="https://www.solarsystemscope.com">solarsystemscope.com </a> - textures of the planets in the Solar system
* <a href="https://sketchfab.com">sketchfab.com </a> - 3D object models
* <a href="https://github.com/1kar/OpenGL-SolarSystem">OpenGL-SolarSystem</a> - 3D C/C++/OpenGL/GLFW Simple Solar System model

# Release
<b>SolarSystem 1.0 </b>can be downloaded from: 
|Version (<b>1.0</b>)|  [SolarSystem.zip](https://github.com/antonmilev/Test2/raw/refs/heads/main/install/SolarSystem.zip)|
|---|---|
|User Manual| [SolarSystem.pdf](docs/SolarSystem.pdf)|
