# **Spider Gen Documentation**

This is a procedural spider generator using geo nodes featuring thorough customization options, LODs and automatic UVs



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img width="723" height="513" alt="piac2" src="https://github.com/user-attachments/assets/7d43ee9e-f979-4bf8-9178-b92513eb0189" /> <img width="627" height="435" alt="pic1" src="https://github.com/user-attachments/assets/e940c210-2338-4d36-aac3-e9eac7fc6d42" />
<img width="1334" height="260" alt="pic4" src="https://github.com/user-attachments/assets/63e01b6a-fb27-4345-889d-b5ceb811946f" />
<img width="638" height="426" alt="pic3" src="https://github.com/user-attachments/assets/a290eb91-edf1-4cb6-b1ae-907d98903797" />

* Customizable values include:

  * Abdomen size
  * Carapace size
  * Carapace offset: The carapace's position relative to the origin, which is also the center of the abdomen
  * Leg Length
  * Leg Radius: The thickness of the legs
  * Legs Per Side
  * Eye Count
  * Eye Distribution Seed: The random seed for the placement of the eyes
  * Eye size: The base size of the eyes, there is some randomization 
  * Fangs: you can choose between curved, straight, or no fangs
  * Fang spacing: the distance between the 2 fangs
  * Fang length
  * Fang size
  * Fang rotation
  * Pack UVs?: Whether to pack all UV islands into one UV space or to let each mesh occupy one whole UV space
  * Detail level: how much geometry detail (for LODs)
 
Built in blender version 5.2.2

Watch out for high levels of geometry, anything beyond 5 detail levels is unnecessary and will slow your machine down
High carapace offset will make the fang placement look scuffed

How to use:
Install the zip and unwrap, open the blend file and set the parameters you want. Duplicate the mesh and change the detail level for LODs. Export as fbx and import into your game engine of choice.




