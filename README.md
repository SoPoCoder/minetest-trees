# Minetest Trees
Tree schems (as well as bushes, logs and boulders) that can be loaded into Minetest using the WorldEdit tool. Includes a wider variety of tree shapes and sizes using all native nodes (no mods required).

![trees_demo](https://user-images.githubusercontent.com/7158003/124171726-83de2980-dadb-11eb-8476-786bf555fb8e.jpg)

### Dependencies:
To load the schem files into your Minetest world you will need the [Minetest-WorldEdit tool](https://github.com/Uberi/Minetest-WorldEdit)

### Demo Instructions
1. Drop the "trees" folder into the "worlds" folder(i.e. /minetest/worlds/)
2. Launch Minetest, select the "trees" world and click "Play Game".
3. Placards at the foot of each tree show the file name for purposes of loading via WorldEdit.
4. Note that tree variations (including logs) are named using a numerical suffix for the purpose of randomizing when using these schems with the realterrain mod. Logs for each tree type (except for bonsai and marsh) end in one (i.e. acacia1).

### WorldEdit Instructions
1. Drop the schems folder into the root folder of the world you wish to add trees to (i.e. /minetest/worlds/myworld/)
2. If you haven't already, enable the Minetest-WorldEdit mod for the world you wish to add trees to
3. Consider where you wish to place your tree/bush/log/boulder. The WorldEdit tool always places schems with the bottom-most southwest corner of the schem at position 1, regardless of where position 2 happens to be. To ensure that your trees trunk is located where you expect it to be, use the following chart showing shema volume to determine where you should place position 1 before loading the schem. Note that the area of every schem is a square, that is the x and z lengths are identical. All bushes have an area of 4 blocks by 4 blocks.

| Schem File Name       |   x   |   y   |   z  
| ------                | ----- | ----- | -----
| acacia1               | 9     | 1     | 9 
| acacia2               | 9     | 6     | 9 
| acacia3               | 9     | 7     | 9 
| acacia4               | 9     | 8     | 9
| apple1                | 7     | 1     | 7 
| apple2                | 7     | 9     | 7 
| apple3                | 7     | 13    | 7 
| apple4                | 7     | 13    | 7 
| aspen1                | 7     | 1     | 7 
| aspen2                | 7     | 11    | 7 
| aspen3                | 7     | 15    | 7 
| aspen4                | 7     | 18    | 7 
| bonsai                | 9     | 9     | 9 
| boulder1              | 5     | 7     | 5 
| boulder2              | 9     | 6     | 9 
| cactus1               | 5     | 1     | 5 
| cactus2               | 5     | 8     | 5 
| cactus3               | 5     | 8     | 5 
| cactus4               | 5     | 8     | 5 
| gpine1                | 5     | 1     | 5 
| gpine2                | 5     | 15    | 5 
| gpine3                | 5     | 17    | 5 
| gpine4                | 5     | 18    | 5 
| gtree1                | 9     | 1     | 9 
| gtree2                | 9     | 14    | 9 
| gtree3                | 9     | 16    | 9 
| gtree4                | 9     | 18    | 9 
| jungletree1           | 7     | 1     | 7 
| jungletree2           | 7     | 13    | 7 
| jungletree3           | 7     | 15    | 7 
| jungletree4           | 7     | 17    | 7 
| marshtree             | 9     | 12    | 9 
| pine1                 | 5     | 1     | 5 
| pine2                 | 5     | 11    | 5 
| pine3                 | 5     | 14    | 5 
| pine4                 | 5     | 16    | 5 
| spine1                | 7     | 2     | 7 
| spine2                | 7     | 6     | 7 
| spine3                | 7     | 12    | 7 
| spine4                | 7     | 15    | 7 
| spruce1               | 9     | 1     | 9 
| spruce2               | 9     | 7     | 9 
| spruce3               | 9     | 12    | 9 
| spruce4               | 9     | 16    | 9 
| big_acacia            | 14    | 10    | 14
| big_birch             | 14    | 10    | 14
| big_jeffrey           | 11    | 25    | 11
| big_jmaple            | 19    | 20    | 19
| big_jungle            | 9     | 27    | 9
| big_oak               | 19    | 20    | 19
| big_sspruce           | 11    | 17    | 11
| big_wpine             | 19    | 25    | 19

![graph](https://user-images.githubusercontent.com/7158003/124072094-ea7b2d00-da72-11eb-856d-36280ba0bd2f.jpg)

### World Edit vs. Minetest Schematic
Two types of schems can be created and used by the Minetest-WorldEdit tool:
- World Edit File (.we): larger than .mts, takes note of air nodes and does not replace the existing map where air nodes are present in the loaded schem. Use chat command "//load [filename]" (no quotes and no extension) to load
- Minetest Schematic File (.mts): smaller than .we, does not care what is within the schem file, it will replace everything in the world in which it is loaded that falls within its volume. Use chat command "//mtschemplace [filename]" (no quotes and no extension) to load

### Example Biomes Generated Using Tree Schems
![example1](https://user-images.githubusercontent.com/7158003/124072107-ecdd8700-da72-11eb-8dc2-5e3f6c63934c.jpg)
![example2](https://user-images.githubusercontent.com/7158003/124072109-ecdd8700-da72-11eb-918f-bea908d3daca.jpg)
![example3](https://user-images.githubusercontent.com/7158003/124072112-ed761d80-da72-11eb-8f7e-5cb925e3fb1c.jpg)