# OpenIGSB
My attempt to reverse engineer the game engine for I've Got Some Balls by Sebastian Aaltonen and reimplement it for modern systems.

## Current Status
I am still going through disassembly to find out the level file format, once this is done, I will start working on the de-facto implementation.

Docs on the file formats, etc. IGSB uses will be uploaded here as I learn more about how they work.

## TODO List
 - [ ] Document level format and make a viewer tool
   - [ ] Potentially make a level editor?
 - [ ] Get title screen showing
 - [ ] Reverse engineer the collission response and marble handling code
 - [ ] Get the rest of the game working as close to original as possible.

## Want to do
 - [ ] Add optional real-time shadow mapping
 - [ ] Add optional elongated marble bug fix
 - [ ] Add optional rigid body physics system
 - [ ] Increase allowed geometry density of maps
 - [ ] Allow maps to use PBR (via extended format or glTF)