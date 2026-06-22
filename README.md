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
