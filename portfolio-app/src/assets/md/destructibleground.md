# Destructible Ground

Here I made a ground that you can destroy if you throw bombs on it. 
You can change the bombs from size and you can also reset the map to it's initial sprite

## What did I do and learn? 

### Collision

Collision is actually quite simple in this one. It will check the next position, and if it detects an object there, it will half the distance until it finds a position it can move to.

### Generate Sprite

I never worked with generating a sprite by getting and setting the pixels. I used the mipmap to get all the pixels and its colors. 
After that i set those pixels to another sprite to clone it and as last i put the cloned sprite as the initial sprite.

### Animations

It might be a surprise considering how extremely good the game looks (lol), but everything is drawn by 
me. Contrary to what others say, nothing has been rotoscoped, although I did use the jump animation from
Prince of Persia as reference, which was also an inspiration to this game. For the rest, I just looked up
videos of people, or googled images of them in certain poses as reference to draw those poses in my
game. Neat.

### State Machine 

Game maker has a ridiculously easy way of making a state machine. You just make a variable with a reference to the script, and call it with `script_execute`.
That's it. You can use references of the current object in that object! Extremely easy to do so. But yeah, I learned this.