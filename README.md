# Lets-Make-A-Voxel-Game
This is where I backup the Let's Make A Voxel Game series. Note that it won't follow the code created in the videos exactly because I started doing this *much* later than I should have...

00 - BasicTerrainGeneration. This simply generates the chunks with the blocks. I have started implementing lighting, but I am running into an issue where the light needs to propogate "out-of-bounds" and it is too slow currently.

01 - Cave Generation And Atlasing. I added a way of stitching textures from the Resources folder together. The reason I use resources and not streamingAssets is because converting a texture from grayscale to a normal map needs to be done in the editor, so the only way to have normal maps would be to read the pixels and serialize them to a .png in streamingAssets, make them by hand, or to just read them from a Resources folder. I also implemented block placement, and structure generation. 
