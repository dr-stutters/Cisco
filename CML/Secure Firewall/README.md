# How To
## Create Node and Image Definitions
I've assumed you've already downloaded the FTDv and FMCv qcoz images
I've also assume dyou've downloaded the Node definitions from here https://github.com/CiscoDevNet/cml-community/tree/master/node-definitions/cisco/ngfwhttps://github.com/CiscoDevNet/cml-community/tree/master/node-definitions/cisco/ngfw 

1. Login to CML 
2. Tools > Node and Image Definitions
3. Click Node Definition
4. Import the ftdv.yaml definition
5. Click on Image Definitions
6. Manage
7. Upload the FTDv qcow image
8. Once uploaded, Create New Image Definition
9. Call it whatevern you want, i called mine... FTDv
10. Ensure the Disk Image is the FTDv you just uploaded
11. node definition, select the node you created above
12. Click on Create

Repeat for FMC

## 
