# GMAP_map_library
A collection of maps to use in the GMAP program. The GMAP installation comes with a few maps already, any others can be found here. Have you created your own map? Please share it here!

## Important notes:
- Installation instructions can be found further down.
- Some maps require other maps to function, some might need you to compile a c-library. In any case, **make sure you read the README of every map** you download **carefully**, to see if it requires any further steps/attention.
- When accepting maps from other users, we (GMAP development team) cannot always test/verify scientific accuracy. We will try to confirm safety/applicability of maps as much as possible, but the final responsibility lies with map creators.

## Guided Tour
Welcome! To use any of the files here, you'll need a working GMAP installation. The development version of GMAP can be found [here](https://github.com/lacourjansenlab/GMAP_development), a stable release repository is coming soon. After you downloaded and installed GMAP, you can pick your favorite maps. Here follows an overview of the files in this repository:

### Singles
The singles directory contains all maps that deal with calculating properties of a single type of chromophore. A singles map might calculate absorption frequencies (diagonal elements of the Hamiltonian), transition dipole moments, raman tensor, and provide the position of the chromophore. Without an active singles map, GMAP cannot function.

### Pairs
The maps in the Pairs directory define how a pair of chromophores should be treated. In other words, a pairs map calculates the couplings between singles maps. Some pair maps are explicitly designed for a specific type of single, while others are more generic. Some general maps can work with any singles out of the box, others might require some support/help from the authors of the singles maps.

### other files
Some maps share certain traits and information. This is stored in files in the main mapdir, instead of in the 'Singles' or 'Pairs' sub directories.

## How to install and use maps
1. Make sure you installed GMAP using its instructions.
2. Using GMAP Setup, create a maps directory. Within the maps directory, you should find two folders: a 'Singles' and a 'Pairs' folder.
3. Download any maps from this repository into your own mapping directory. Any maps found here in 'Singles' should be put in the 'Singles' directory, and the same with the 'Pairs' maps. Tools like [download-directory](https://download-directory.github.io/) make downloading a single directory from a full repository easier, but are not created/supported/developed/endorsed by the GMAP development team.
4. Confirm in the map README whether there are any further steps needed to get the maps running. For example, downloading additional maps (go through these same installation instructions for each) and/or compiling a c-library.
5. In your input parameter file (or on the command line) use the parameter `map_directory` to tell GMAP to use your newly created maps directory, including your freshly downloaded maps. This line needs to be present in any input file using your newly downloaded maps. While multiple map directories can be specified here it is generally discouraged to do so without good reason as it may become unclear which map was actually used. The program does not allow you to choose which edition to pick if a map of the same name occurs in multiple provided directories!
6. Now, the maps are ready to use! Don't forget to select them using the `maps_to_use` parameter! 

## How to share your map with us

If you're a member of the lacourjansenlab organization (and a physical member of our group), it is more convenient to work through issues and branches. Please just come to my office to discuss.

If you're not a member of our group, please do the following instead:
1. Create a fork of this repo.
2. Add your map to your fork of the repo. Make sure the map is tested with GMAP and works without errors. Also make sure it gives the correct results. The 'checklist' page in the GMAP repo can help with this. (click 'customizable maps' in the built documentation, or go to the adding_a_new_map directory in the documentation files).
3. Open a pull request from your fork to the original repo on lacourjansenlab (to the main branch).
4. A member from our organization will review the map, and might request changes.
5. Make sure to answer any questions clearly, and make changes where needed.
6. After any necessary changes are made, we will complete the request and add your map to the repository.
