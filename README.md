## 3D Solar system
Delevoper: Daniel Milev <br>

<a href="https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip">Download</a>

## Introduction


The project aims to develop a 3D simulation of the Solar System using OpenGL and modern multimedia technologies. This simulation will facilitate learning about the geometry, positions, and orbital speeds of planets and their moons. Additionally, it offers an overview of the Asteroid Belt, situated between Mars and Jupiter, which holds significant potential for future study and resource utilization.

The simulation begins with a free camera that enables movement and rotation in 3D space using the mouse and keyboard. By pressing the number keys 1-9, users can switch to orbital cameras positioned at fixed locations relative to the nine planets. Additionally, there are six stationary cameras dedicated to specific moons and the Asteroid Belt.

The application lets you adjust the simulation speed or pause it at any chosen moment, enabling a detailed study of celestial body movements. It also provides the option to visualize the orbits of planets and their moons.

While many dream of traveling to space, and I hope it becomes a reality in the near future, the 3D Solar System simulation offers the chance to pilot a virtual spaceship, exploring destinations from the Sun to Pluto.

<div align="center">
<img src="pics/start.jpg" width="854px"/>
</div>

## Main stages in the implementation of the project

- Defining an idea
- Presenting to the manager
- Determining technical means for development
- Planning and shaping the project
- Developing functionality
- Testing and correction
- Publishing and sharing

## Used technologies

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

## Advanced graphics technologies

- <a href="https://learnopengl.com/Advanced-OpenGL/Cubemaps">CubeMap texturing </a>
- <a href="https://learnopengl.com/Getting-started/Textures">MultiTexturing </a>
- <a href="https://learnopengl.com/Advanced-OpenGL/Instancing">Instancing </a>

## Logical and functional description of the application

The program allows you to view different viewpoints and moons, change cameras and various other changes with these buttons, you can remove or add orbits, launch a special mode for additional information, etc.

### Keyboard
 - /(? - help menu
 - WASDQE - camera movement.
 - Arrow keys - rotate the view in the direction of the X and Y axes.
 - < > - rotate the view in the direction of the Z axis.
 - 1 - 0 on the keyboard - change the camera to the planet view
 - 1 - 6 on the numeric keypad - change the camera to the moon view
 - R - change the background.
 - O - show and hide the orbit
 - P - pause
 - J - change the camera to the side view (in planet view)
 - K - show the spacecraft
 - L - change the language
 - (+, - ) - change the simulation speed
 - Space - return to the standard point of view
 - F1 - switch to free camera
 - X - show additional information (in planet view)
 - F - switch to full screen
 - NM - change the number of asteroids
 - HG - change the number of Kuiper asteroids
 - Z - show axes
 - B - show the asteroid belt
 - V - show Kuiper belt


### Mouse
- left button - rotate view
- scroll button - zoom in/out
- right button - move view
  
## Asteroid belt

Asteroid belt view is activated by pressing the 0 key:

<div align="center">
<video src="https://github.com/user-attachments/assets/f63e7cb0-1657-48f6-b470-97596ece2d42" />
</div>

Detailed info of asteroids can be activated with X key:

<div align="center">
<img src="pics/AsteroidsInfo.jpg" width="854px"/>
</div>

## Kuiper asteroids

<div align="center">
<video src="https://github.com/user-attachments/assets/77ab0257-cefe-4d0a-9bcc-c3d20e070573" />
</div>
  
There is a kuiper's belt view with the 0 key on the digits keyboard:

<div align="center">
<video src="https://github.com/user-attachments/assets/0866b541-ef37-42ba-998a-e3506b4e6116" />
</div>

The additional information about the Kuiper Asteroid Belt is displayed by pressing the X button

<div align="center">
<img src="pics/AsteroidsKuiperInfo.jpg" width="854px"/>
</div>

## Saturn Belt

Saturn belt is compose from three sub belts known as A,B and C.
<div align="center">
 <video src="https://github.com/user-attachments/assets/5fe0d665-2acf-41b8-b2ae-a558ace83785"/>
</div>
   
Camera travel view is started by pressing the F7 button.

<div align="center">
<video src="https://github.com/user-attachments/assets/2155c13e-c825-4a8c-8121-8c39edd8124c" />
</div>
 
The display of planet orbits can be toggled on and off using the "O" key, and this feature works in both normal and planet views.

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

| <img src="pics/Ganymede2.jpg" width="300px"/> | <img src="pics/Callisto2.jpg" width="300px"/>|<img src="pics/Rhea2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Ganymede - KeyPad:4 </b>* | *<b>Callisto- KeyPad:5 </b>* | *<b>Rhea - KeyPad:6 </b>* | 

| <img src="pics/Titan2.jpg" width="300px"/> | <img src="pics/Oberon2.jpg" width="300px"/>|<img src="pics/Triton2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Titan - KeyPad:7 </b>* | *<b>Oberon- KeyPad:8 </b>* | *<b>Triton - KeyPad:9 </b>* | 

In planet and moons views there is additional information about the objects displayed with X key:

| <img src="pics/EarthInfo.jpg" width="300px"/> |  <img src="pics/MarsInfo.jpg" width="300px"/> | <img src="pics/PlutoInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Earth - Key:3+X</b>* | *<b>Mars - Key:4+X</b>* | *<b>Pluto- Key:9+X</b>* | 

| <img src="pics/MoonInfo.jpg" width="300px"/> |  <img src="pics/CallistoInfo.jpg" width="300px"/> | <img src="pics/TritonInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Moon - Key:KP 1+X</b>* | *<b>Callisto - Key:KP 6+X</b>* | *<b>Triton- Key:KP 9+X</b>* | 

Again J and O keys can be used to display planet orbits:

<div align="center">
 <video src="https://github.com/user-attachments/assets/be601eb0-3a3f-4d38-9db4-617e6e57750a" />
</div>

<div align="center">
 <video src="https://github.com/user-attachments/assets/3f7a4180-77c4-4103-9bba-f2391ade11f0" />
</div>






## More to come..

<ul>
  <li>Spacehip travel around the solar system </li>
  
  | <img src="pics/Spaceship1.jpg" width="300px"/> |  <img src="pics/Spaceship2.jpg" width="300px"/> | <img src="pics/Spaceship3.jpg" width="300px"/> 
  |:---:|:---:|:---:|
  <li>Selection of planets and interaction </li>
  <li>Showing planets internal structure</li>
</ul> 

## Drew inspiration from
* <a href="https://learnopengl.com">learnopengl</a> - extensive tutorial resource for learning OpenGL
* <a href="https://www.solarsystemscope.com">solarsystemscope.com </a> - textures of the planets in the Solar system
* <a href="https://sketchfab.com">sketchfab.com </a> - 3D object models
* <a href="https://github.com/1kar/OpenGL-SolarSystem">OpenGL-SolarSystem</a> - 3D C/C++/OpenGL/GLFW Simple Solar System model

## Release
<b>SolarSystem 1.0 </b>can be downloaded from: 
|Version (<b>1.0</b>)|  [SolarSystem.zip](https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip)|
|---|---|
|User Manual| [SolarSystem.pdf](docs/SolarSystem.pdf)|

## System Requirments

Windows OS 10/11
<br>
Video card supporting OpenGL 4.x and 1GB memory
