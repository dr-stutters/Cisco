# How To
## Create Node and Image Definitions
I've assumed you've already downloaded the FTDv and FMCv qcoz images
I've also assume dyou've downloaded the Node definitions from here https://github.com/CiscoDevNet/cml-community/tree/master/node-definitions/cisco/ngfwhttps://github.com/CiscoDevNet/cml-community/tree/master/node-definitions/cisco/ngfw 

Login to CML
Tools > Node and Image Definitions
Click Node Definition
Import the ftdv.yaml definition

Click on Image Definitions
Manage
Upload the FTDv qcow image
Once uploaded, Create New Image Definition
Call it whatevern you want, i called mine... FTDv
Ensure the Disk Image is the FTDv you just uploaded
node definition, select the node you created above
Click on Create

Repeat for FMC

## 
