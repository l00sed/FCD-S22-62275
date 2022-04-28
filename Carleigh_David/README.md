# Lucid
![image](/Carleigh_David/img.png)
<p align="center">
    <p align="center">Project by Carleigh Cusick and David Warfel </p>
<p align="center">
      <p align="center">Located in the Numbers Garden currently on CMU's campus, Lucid aims to create a new space, a quiet environment where people can relax, read or take a nap. On the facade, two zones are created by determining the distance between the panels and the sun in turn splitting the space into a reading and a sleeping area. The reading area requires more light and therefore uses more transparent panels while the sleeping areas use more opaque and translucent panels in order to remain darker. Additionally, the inner facade replicates the feel of its exterior counterpart however slopes into a sleeping and resting area formed to comfortably fit the human form.</p>

<p align="center">The space frame consists of joints that connect six members in order to create the intricate form. The pipes interlock with the joint through dowels to secure the pieces in place. The triangular modules of the two layers of the space frame are connected with vertical members in the center of the joint, allowing for two sets of facades to be attached to both the exterior and the interior of the structure. This project aims to understand the responsiveness and fabrication of a new pavilion on campus. </p>
</p>

**Contents**

- [Lucid.pdf](/Carleigh_David/M6Lucid.pdf) of M6 submission
- additional [Folder of Gifs](https://drive.google.com/drive/folders/15OfFYhpsMLj67I-ZToxW7TAEFUgf18a-) or animated content
- [FCD_M6.gh](/Carleigh_David/FCD_V6.gh) script file 
- [FCD_M6.3dm](https://drive.google.com/drive/folders/1IkzBHXBOR2uFnrBsR8Qs0_MQXAey9vmy) CAD model File
- this [Text](/Carleigh_David/README.md) README File

## Instructions for Use

This project uses a _Grasshopper_ script&mdash; which is a file that contains the algorithm to generatively design our spaceframe and placement of planels on facade. You must have Rhino 7 to open the [FCD_M6.3dm](https://drive.google.com/drive/folders/1IkzBHXBOR2uFnrBsR8Qs0_MQXAey9vmy) file due to the use of multipipe which is native to this version of the software.

The Grasshopper file uses a base surface in order to create panels and a space frame through triangulation. The script then uses the position of the sun in order to create two zones which will determine the amount of light entering the space. The first zone will contain more transparent and translucent panels letting in more light compared to the second zone which will contain more opaque panels.

All parameters in the Grasshopper file will be located on the left side of the file in red boxes and are labeled by their functions. Actions include changing the numbers of panel/ density of the space frame, changing the frame member’s thickness, variation in different types of panels, and finally how big each zone is.

**Dependencies**

The _Grasshopper_ script uses:
  - Lunchbox

The plugin Lunchbox was used in the Grasshopper script in order to easily triangulate the original surface and create the freedom to choose the desired amount of panels throughout the structure.
Install this dependency and then open the [FCD_M6.gh](/Carleigh_David/FCD_V6.gh) file in Rhino3D.

## 3D Assets and Organization

Once the desired outcome was reached in Grasshopper, the structure was baked into Rhino. The surrounding topography and context was constructed using 3D modeling tools, models from Sketchup, and google images. The space frame and panels were organized into layers to add materiality for rendering and simulations. 

## Reference and Acknowledgements
3D model for College of Fine Arts context building from Sketchup Warehouse modeled by Nick D.
