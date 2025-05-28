# game-programming-exp-08
# NAME:RAMPRASATH
# REG NO:212223220086

## AIM:
To create a landscape in Unreal Engine, apply a custom landscape material, and add foliage for
realistic environment generation.
## PROCEDURE
1. Create a New Landscape:
Open your Unreal Engine project.
Go to the Modes Panel and select Landscape.
Set the desired section size, number of components, and overall resolution.
Click Create to generate the landscape.
2. Apply a Landscape Material:
In the Content Browser, create a new Material and name it M_Landscape .
Open the material and:
Use Landscape Layer Blend to blend textures (e.g., grass, rock, dirt).
Connect appropriate texture samplers to different layers.
Output the final blend to the Base Color, Normal, and optionally Roughness inputs.
Save the material.
Select the landscape in the scene, go to the Details Panel, and assign M_Landscape to
the Landscape Material slot.
3. Add Foliage:
Go to the Foliage Mode from the Select Mode dropdown.
In the Foliage Panel, click the + icon to add Static Meshes (e.g., trees, grass, bushes).
Adjust settings like Density, Scale, and Randomness.
Use the brush tool to paint foliage onto the landscape.


## Output:
![image](https://github.com/user-attachments/assets/cb707c5d-f999-4636-948f-ab8a23a99005)
![image](https://github.com/user-attachments/assets/8ab15309-1129-4e34-a744-76f95b0cff2b)

## RESULT:
A landscape was successfully created and enhanced with:
 ->A layered, textured material using M_Landscape .
 ->Static mesh foliage such as trees and grass for realism. This setup provides a foundation for Open-world levels, terrain-based gameplay, or environmental simulations in Unreal Engine.




