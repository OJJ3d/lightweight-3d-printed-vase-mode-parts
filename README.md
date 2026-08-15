We are making a remote controlled sailboat using the new vase mode + ribs that we developed. Here
is a brief explanation of what is new compared to traditional vase mode with ribs and our, and a
tutorial. Make sure to watch the video here:

https://drive.google.com/drive/folders/1verP1uEe15y1
qu4991YVATYrRwpX1hgG it explains the design process with visuals.

Traditional vase mode with ribs parts have a vertical planar divide that splits the ribs in half, this
severely weakens parts made like this, in bending and shear stress. The two main reasons for using
vase mode and ribs are to produce lightweight parts and to enable the use of foaming filaments that
are hard to print not in vase mode. This means they are often used for wings and fuselages of 3d
printed remote controlled planes, where the wings are subject to bending loads. As such the divide is
a limiting factor on remote control planes. We are making a remote control sailboat which similarly
experiences large bending moments.

To fix this issue we have developed a system wherein the plane of the divide alternates by a few
millimetres every 2 layers, as such a zipper seam is created over where the divide would usually be,
largely eliminating the weakness.

To acheive this we use 3 steps:
  1. create your model, orient the normal of the xy plane up (print z direction)
  2. using a square pattern of diamonds or triangles with small gaps (0.1mm) and intersect with the target bodies
  3. make a stack of 2x line width horizontal and 2x layer height vertical recttangles in a zigzag pattern (with some overlap, 0.1mm)

tips:
  1. It will make hundreds of bodies at least so will be laggy, be patient
  2. make sure you are alligned to grid
  3. do as much in scetch as possible

For the boat specifically we looked at many different catamaran hull shapes and tried to emulate them with our design. We also used a 0.8mm nozzle for more strength though this method is compatible with all nozzle sizes. For the wingsail we used a naca 0010 profile and the same vase mode technique, adding a spar hole and solid printed parts for the stays (cable supports on either side of the mast), it will be printed in lw-pla or lw-asa.

print settings for the hulls (vary by printer capabilites, I use a sovol sv08):
vase mode
8000mm/s^2 accel
250mm/s speed
0.4mm layer height
slight overtemperature of material for better bonding (go to the top of the suggested range of temparture)
5% overextrusion for better layer bonding

print settings for the wing
vase mode
8000mm/s^2 accel
100mm/s speed
0.4mm layer height
maximum temperature
5% overextrusion (remember to tune extrusion to the expansion of the filament!)

The way in which we join hull segments is still under development, right now we are using thermal welding (melting both ends and pressing them together) but we find this a bit imprecise and weak so we are experimenting with solvent welding, gluing and scarf joints. 

images:





