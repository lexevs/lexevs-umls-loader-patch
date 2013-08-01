lexevs-umls-loader-patch
========================
This patch will allow for LexEVS (version 5.1 and up) to load the updated
UMLS RRF files via the LexEVS UMLS and Meta loaders.
		
		
Build
-----
Run ```git clone https://github.com/lexevs/lexevs-umls-loader-patch.git```
Run the command ```ant build``` from the top level directory of this project.
The resulting patch jar will be located in ```dist/lbPatch.jar```. 

Install
-------
Copy ```lbPatch.jar``` jar file to the ```runtime/``` directory of a LexEVS installation.
