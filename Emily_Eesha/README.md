# Pockets Full of Sunshine

<p align="center">
    <img src="https://user-images.githubusercontent.com/23065167/163903918-9d8c0cf8-3e32-4224-be9a-24e77a0e0f5f.png" />
    <p align="center">Project Example by Teaching Assistant, Mitchell Foo</p>
</p>

This is an example project in the FCD S22 repo. It is meant to demonstrate the correct format and content expected for uploading materials. This area is used to reiterate the project description from my M6 submission. I could also describe the M6 prompt. 

**Contents**

- `.pdf` of M6 submission
- [`.gifs`](https://drive.google.com/file/d/1xtq6UDDhdwftuJCevF2du4K4EWiN7Viy/view?usp=sharing) of assembly of pavillion
- [`.gh`](https://drive.google.com/file/d/1xRKs4cQALHKaU2EkoSQzO58Y2_immf2R/view?usp=sharing) script file
- [`.3dm`](https://drive.google.com/file/d/1xGP8pP1VEcUayYtYQko_7h4uINvXKOhH/view?usp=sharing) CAD model file
- this [`.md`](https://github.com/l00sed/FCD-S22-62275/tree/main/Emily_Eesha) README

## Instructions for Use

To model this project, Grasshoper, along with the aid of a few plug-ins are used to model the pavillion. Serveral parameters within the Grasshopper program allow for the adjustment o fhte space-frame design, such as its shape, size, and thickness. The main parameters are listed below...

The programs starts from a defined surface and then divides or triangulates; these divisions become the base geometries for the connections of the space-frame and the shading devices. 

    Min Division Length: smallest length of triMesh division (low value makes more divisions)

    Vert Factor: verticle displacement factor of brep

    Member Thickness: thickness of each beam in the space-frame

    Index: reference to a surface 

    Radius Top: the radius of the top circular opening of the shading device

    Radius Bottom: the radius of the bottom circular opening of the shading device

    To run the [`.3dm`](https://drive.google.com/file/d/1xGP8pP1VEcUayYtYQko_7h4uINvXKOhH/view?usp=sharing) file, you must have Rhino 7.

**Dependencies**

The _Grasshopper_ script uses:
  - Lunchbox
  - Kangaroo
 
Install these dependencies and then open the [`.gh`](https://drive.google.com/file/d/1xRKs4cQALHKaU2EkoSQzO58Y2_immf2R/view?usp=sharing) file in Rhino3D. 

