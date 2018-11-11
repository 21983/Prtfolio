# Destructible Ground

Here I made a ground that you can destroy if you throw bombs on it. 
You can change the bombs from size and you can also reset the map to it's initial sprite

## What did I do and learn? 

### Generate Sprite

I never worked with generating a sprite by getting and setting the pixels. I used the mipmap to get all the pixels and its colors. 
After that i set those pixels to another sprite to clone it and as last i put the cloned sprite as the initial sprite.

### Change sprite and collider

The hole is made by a collider. It checks where the hole should be created and how big the collider is of the bomb and it sets the pixels to transparent and it changes the collider by getting the physics shape and setting the path of the new collider.