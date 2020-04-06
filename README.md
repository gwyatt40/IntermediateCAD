# Intermediate CAD

## Design Tables

  ### Description
 Goal: The goal was to use design tables to create 7 different configurations of a spool part with varying sizes and numbers of holes. 
Steps: I first built a cylinder with a large circular cap at one end. Then I added 6 holes around the perimeter of the cap, using a pattern function, as well as a fillet at the edge. I then added a #12 counterbored hole to the center of the cylinder, and mirrored that hole, the cap, and all other details (perimeter holes, chamfer, etc) to the other side. The final step of the project was to create 6 configurations of the spool, in different sizes and with different numbers of holes, using design tables. 

  ### Problems
 - I couldn’t select the dimension that set the number of holes around the spool. I fixed this by zooming out in the display and right clicking the dimension. 
SolidWorks won’t let you create multiple design tables. I made one early on and forgot about it, so I had to go back in and edit it instead of making a new one. 

  ### Pictures

<img src = "https://github.com/gwyatt40/IntermediateCAD/blob/master/Media/DesignTablesMedium.png" width="600">

- This is the medium configuration of the spool part. The other configurations are very similar, with the differences in dimensions that were mentioned in the description. The exceptions are the small and tiny configurations which don't have central counterbored holes. 
  
  ### Lessons Learned
  
- Order your configurations by size in the design table, it makes adding in dimensions/supressing components much easier
- If you have to copy something from Canvas into SolidWorks, write it down or have it open on a seperate computer to save time
- Quantity dimensions may be hard to find so try zooming out the display window in case they're floating somewhere
- If SolidWorks will not let you create a new Design Table, odds are you already have one and can edit it

## Advanced and Mechanical Mates

 ### Description
Goal: The goal was to make an assembly of three rectangular tubes, connected by a pin, that would telescope together as the pin was moved. 

Steps: I began by making 3 configurations of rectangular tubes. All three were made different colors and the largest had a slot down its middle. I then created a basic pin part with a cylindrical center and two caps and the ends. I placed all of these parts in an assembly and lined up all three rectangular tubes using mates. I then used a mechanical slot mate to place the pin part into the slot of the largest rectangle. With the addition of a few more mates, the entire assembly was able to telescope when the pin was moved. 
 
 ### Problems
 - I couldn’t change the color of one configuration without changing the color of the others. I had to go into configuration properties for each individual configuration, select "Use configuration specific color" under Advanced Options, and choose the color I wanted.  Here's a website I found later that outlines these steps in detail: [Configuration Colors How-To](https://www.cati.com/blog/2016/06/solidworks-configuration-specific-color/).
 
 ### Pictures
 <img src = "https://github.com/gwyatt40/IntermediateCAD/blob/master/Media/AdvancedMechanicalAssembly.png" width="600">

- The entire assembly mated together


<img src = "https://github.com/gwyatt40/IntermediateCAD/blob/master/Media/AdvancedMechanicalPin.png" width="600">

- The pin part on its own


<img src = "https://github.com/gwyatt40/IntermediateCAD/blob/master/Media/AdvancedMechanicalTube.png" width="600">


- The largest configuration of the rectangular tube. The other two configurations are without the center slot

 ### Lessons Learned
 - Change configuration colors in configuration properties for individual colors
 - READ INSTRUCTIONS CAREFULLY!!! (Especially for complicated assemblies) 
 - Drop parts into assemblies in specific order, it makes everything much easier to organize
 

