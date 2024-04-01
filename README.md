# Grid-Based-Inventory-System-
Grid based inventory and player upgrade system for an RPG first person shooter 


The system is inspired by "Wrought Flesh"

It is split into multiple classes each responsible for its own element of getting , storing and replacing organs , as well as showing their effects and applying their effects to a player class that is not included in this repository

All classes without "Organ" in the name are responsible for UI showcase , or dragging the organs from inventory to body parts.

There are 2 grid types, 1 for organs as they take up place that can be non-rectangular , and another for body parts and inventory that is exclusively rectangular.

As such there are 2 tile types for body and for individual organs.

The organs are placed on body parts by dragging them on top of unocuppied body part tiles, when it is done those tiles are not occupied and cant be occupied by other organs.


Used this library to create non-rectangular grids: https://github.com/Eldoir/Array2DEditor/tree/master
