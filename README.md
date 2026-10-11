# Minigame 2
## Devlog
1. One error I got when I was writing the code was when I forgot to put a semicolon after declaring the float variable "r" into the spell script. I fixed it by placing the semicolon. As for the if statement, I fixed it by giving the conditional parenthesis. I'm pretty sure that if statement had two errors, but I forgot specifically what the other error was.
2. Based on the fact that the line uses the key word "Color" and the word "SpriteRenderer", I would assume that this line creates a new color given R, G, and B values for a sprite to render. The color is created through a new color instance "new Color(R,G,B);" The period is most likely used to access one of the instances properties (in this case, the color property of the sprite renderer). The word new is used to declare a new "instance"? Because a new color is made every time a box was hit with the spell, I like to guess that a new color was made and then that new color is assigned to the box's sprite.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
