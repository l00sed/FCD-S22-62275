# Trilateral Twists
## FCD-S22-62275
## Jacky Jia & I Lok U 
--- 
![render1](https://drive.google.com/uc?export=view&id=1knaI2kIx4H2Vd8TrurribtoMPDRmvHje)

<p align="center">
    Render View 1

## Content

### Project Description 
#### Trilateral Twists primarily uses the manipulation of triangles to serve programmatic elements and respond to the daylight environment. The pavilion is situated at the grass patch right beside the cross intersection in the cut. As students always occupy the area next to the Fence, we decided to place the pavilion there in order to provide more seating and work space to the community. Rather than using a space frame system solely for structural integrity, the triangularity of the space frame itself insinuates form. Through parametrically experimenting and altering the orientation, rotation, and size of triangular sections along a spline, the strip-like pavillion shapeshifts into different forms that serve different programmatic elements. The sizing of the triangle also determines the size of the panel, thus by increasing the size of the triangles that faces along the sun path, it can provide most efficient shading for the majority of the day while still allowing small seams of light to penetrate through.
![render2](https://drive.google.com/uc?export=view&id=1kFsDeTYfJn0VZpydoYFsBpGWiL5-XRf8)

<p align="center">
    Render View 2

### Construction 
#### The pavilion is divided into two primary layers, the space frame and the panels. The space frame construction is simple: using 1 1⁄4” PVC pipes as connectors and laminated 5” x 5” x 3” wood blocksas joints to connect the PVC pipes. The blocks act as nodes and are placed in every vertice of the pavilion. The panels consist of a fabric material, which are then connected with hooks in each corner. These hooks are then drilled into the laminated block; this allows the fabric material to stretch and maintain its tensile strength. Finally, the two specific sized wooden panels are drilled into both ends of the pavilion, which functions as bench and table.
![render2](https://drive.google.com/uc?export=view&id=1ilSy4F35Aa1CZKdqU0wHE_XzVeME6gTg)

<p align="center">
    Exploded Axon with Materiality

![construction gif](https://drive.google.com/uc?export=view&id=1eDI7qIHFeAyZbrBhLmiE7AyciStQqUNv)

<p align="center">
    Construction Animation

### Solar Analysis  
#### Another factor that drives our design is its responsiveness to the natural environment, specifically daylight. The orientation and sizing of the triangles are placed in a way that provides the most shade under the table by following the sun path. Through the qualitative sunlight analysis the table is shaded 80 percent throughout the day; this is so that people working on the table do not get negatively affected by over brightness and glare.
![render2](https://drive.google.com/uc?export=view&id=17LwyXWO_RkMzTQByaPNMaYIFQOWgXnhw)

<p align="center">
    Solar Analysis from 6 am to 6 pm

### M6 Submission PDF
[M6 PDF](https://drive.google.com/file/d/1t8oWB4yzaB-9wLoxtgXZpH2Z2CQ9pr63/view)

### Rhino File 
![Rhino Screenshot](https://drive.google.com/uc?export=view&id=1N7dqVrzaBMISD_wPIGqQLB7oLZR-YiKT)

<p align="center">
    Rhino Screenshot

[Rhino File](https://drive.google.com/file/d/1fTXAzxtsrYGAvHzemA9Rs3rHZGL4t_rh/view)

### Grasshopper File 
![Grasshopper Screens
hot](https://drive.google.com/uc?export=view&id=1sxETRtWPyMQp0rBM49j1Z0yafUlLn6F_)

<p align="center">
    Grasshopper Screenshot

[Grass Hopper File](https://drive.google.com/file/d/1bgDv1DpN0tMLyD41FO7MJ0eLe6BxFBlu/view)

### Instructions for Use 
#### This project uses a Grasshopper script containing algorithms that generative design both the spaceframe and the panelings of our pavilion. The script is divided into nine groups to allow for easy navigation. Many parts of the algorithm can be parametrically changed to alter the final geometry of the pavilion, including:
* #### The input geometry - determines the overall shape of the pavilion;
* #### The number of division points on the input geometry - determines the density of the triangle primary trusses, the angle of the secondary trusses, the number and placements of the box connectors, and the density of panels;
* #### The offset distance - determines the size of the panels and the length of the box to panel connectors;
* #### The pipe radius - determines the size of the space frame pipes and the size of the panel to box connectors 
#### The Grasshopper script includes no dependencies and can be opened on Rhino 6 and 7. To use, download the .gh file from the link provided; then open it in Rhino3D. 
