# redshift
This module provides a concrete example of packaging Maxon's Redshift as a cpenv module.

It includes two interesting methods of deploying a package based on a DCC's version.
1. Using native DCC packaging files like the houdini .json and maya .mod files in the root directory of the module.
2. Using another module (cinema4d in this case) to set an environment variable specifying the DCC version (C4D_VERSION) to choose the correct plugin folders.

*No redshift binaries are included!* You will need to extract the Redshift plugin yourself into the win and mac folders to make full use of this module.


## Notes
As of Cinema4D R26 I would no longer advise using an external install of Redshift for Cinema4D. Unfortunately, Maxon has more or less baked Redshift into C4D.

This module file still works great for Maya and Houdini though!
