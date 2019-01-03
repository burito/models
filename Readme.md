models
======
This repository contains a bunch of models that I'm using to test my graphics efforts. It exists to simplify the process for people wanting to test my stuff.

If you're looking for data to test your stuff, I'd recommend...

* http://graphics.stanford.edu/data/3Dscanrep/
* https://casual-effects.com/data/
* http://kos.informatik.uni-osnabrueck.de/3Dscans/

The following text is cut & paste from the origin.

Stanford Bunny
--------------
Brian Curless and Marc Levoy created this model from multiple range scans of a real object using a Cyberware 3030 MS scanner. Morgan McGuire converted the file to OBJ, fixed holes, computed smooth vertex normals, and created a texture parameterization in 3DS Max.
* License: Stanford Scan
* © 1996 Stanford University
* Source: [Morgan McGuire's Computer Graphics Archive](https://casual-effects.com/data)

LPS Head
--------
Infinite-Realities Director Lee Perry-Smith created a 3D scan of his head. Morgan McGuire and Guedis Cardenas at Williams College converted the displacement file from .tif to 16-bit .png and created created a low resolution version of the bump map. We set up the .mtl file's texture maps, painted the bump map so that it is seamless at the back of the head, and adjusted the default glossy highlight to better simulate a 3D head.
* License: CC BY 3.0
* © I-R Entertainment Ltd.
* Source: [Morgan McGuire's Computer Graphics Archive](https://casual-effects.com/data)

Crytek Sponza
-------------
The Atrium Sponza Palace in Dubrovnik, re-modeled by Frank Meinl at Crytek with inspiration from Marko Dabrovic's original. I took the OBJ version exported by Meinl, computed bump maps from the normal maps using normal2bump.cpp (since MTL files expect height bumps, not normals), put the "mask" textures into the alpha channel of the associated diffuse texture, cleaned up noise in the masks, corrected the material mapping for the octagonal vases, compressed the textures using PNGcrush, and removed the long untextured banner floating in the middle of the atrium that appears in the file but in none of the published images of the model. The zipfile includes the banner as a separate object.
* License: CC BY 3.0
* © 2010 Frank Meinl, Crytek
* Source: [Morgan McGuire's Computer Graphics Archive](https://casual-effects.com/data)
