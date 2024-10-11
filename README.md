# EarlyStage-LCA
This script can be used to take volume studies in Rhino and define construction amounts for life-cycle inventories.

Approach
- Import geometry to grasshopper
- Add windows
- Separate surfaces into walls, roofs/ceilings, etc. using HBrooms
- Bake geometry to Rhino

The modified geometry is then imported to RealTime LCA. Here the auto-mapping function is used to quickly map materials and create results.
As the detail level is low at this stage, a sufficient buffer should be added to the results.


*Grasshopper plug-ins*
The following plugins are needed. 
- Ladybug Tools version 1.8.0
- EleFront version 5.1.8
- Speckle
  
Make sure to download the exact same version of the plug-ins. The script might not work with other versions.
