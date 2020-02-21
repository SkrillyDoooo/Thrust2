
# Thrust 2

A space adventure. 

## Getting started

1) Pull this repo
2) Open at the repo root with Unity version 2020.1a1 or higher. 
3) Navigate to Assets > Scenes > ControlsPlayground
4) Click the play button at the top


### Controls:


W = add thrust in ship's forward direction  
A = add thrust in ship's left direction  
S = add thrust in ship's backward direction  
D = add thrust in ship's right direction  

Q = add rotational thrust left  
E = add rotational thrust right  

Z = Activate/Deactivate dampers (dampers will counter-act ship's forces making it easier to pilot, however, you may just want to coast.)  

Scroll wheel = zoom in and out on map  


## GravGrid:
- Check out the GravGridBuilder.cs to see the root of the implemetation. It's a bit of a mess due to major feature sprint to get infinite grid and the tessalation working. Planning to clean this up later. The basic job loop can be found in the Update function


