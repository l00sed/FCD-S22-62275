# Pockets Full of Sunshine

<p align="center">
    <img src="https://user-images.githubusercontent.com/104486299/165774080-50206233-4173-442e-b82d-61eb38ba2776.jpg" />
    <p align="center">Location: In the South-West corner of the field in front of CFA. </p>
</p>

Given the site that we chose (shown in the image on the right), which is nestled in between Hunt Library and CFA, we were tasked with finding the purpose fore area that no longer has a large tree. We chose to create a space that offers connections to the ground while also growing from the ground. By using an undulating curve that draws viewers eye up, to the seating oppurtunities, the shaded spaces and the felxible zones for play under and over the curves the site is activated. The nature of the space frame and shaded devices allow for the sun to shine into shaded spaces at certain times of the day through the cut outs, however it is filtered and in specific zones that ensure that it is not to harsh. Within the space frame, there are LEDS that turn on at night and allow the structure to remain useable for people to come and study, lounge, meet up with friends and for children to continue playing on. There are also spaces for plantings in the niches that touch the ground. Overall, the structure reactivates the space to create a more useful zone for the CMU community to engage with as well. 
**Contents**

- [`.pdf`](https://drive.google.com/file/d/11FAvenbty9WGYZ0gjfnQVkpJN0p2zCf4/view?usp=sharing) of M6 submission
- [`.gifs`](https://drive.google.com/file/d/1xtq6UDDhdwftuJCevF2du4K4EWiN7Viy/view?usp=sharing) of assembly of pavillion
- [`.gh`](https://drive.google.com/file/d/1xRKs4cQALHKaU2EkoSQzO58Y2_immf2R/view?usp=sharing) script file
- [`.3dm`](https://drive.google.com/file/d/1xGP8pP1VEcUayYtYQko_7h4uINvXKOhH/view?usp=sharing) CAD model file
- this [`.md`](https://github.com/l00sed/FCD-S22-62275/tree/main/Emily_Eesha) README

## Instructions for Use

To model this project, Grasshoper, along with the aid of a few plug-ins are used to model the pavillion. Serveral parameters within the Grasshopper program allow for the adjustment og the space-frame design, such as its shape, size, and thickness. The main parameters are listed below...

  Min Division Length: smallest length of triMesh division (low value makes more divisions)

  Vert Factor: verticle displacement factor of brep

  Member Thickness: thickness of each beam in the space-frame

  Index: reference to a surface 

  Radius Top: the radius of the top circular opening of the shading device

  Radius Bottom: the radius of the bottom circular opening of the shading device

The programs starts from a defined surface and then divides or triangulates; these divisions become the base geometries for the connections of the space-frame and the shading devices. 

To run the [`.3dm`](https://drive.google.com/file/d/1xGP8pP1VEcUayYtYQko_7h4uINvXKOhH/view?usp=sharing) file, you must have Rhino 7.

**Dependencies**

The _Grasshopper_ script uses:
  - Lunchbox
  - Kangaroo
 
Install these dependencies and then open the [`.gh`](https://drive.google.com/file/d/1xRKs4cQALHKaU2EkoSQzO58Y2_immf2R/view?usp=sharing) file in Rhino3D. 

