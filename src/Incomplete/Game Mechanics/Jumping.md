How does jumping work???

The player has a jump count of 2 when connnected to ground. falling or jumping from the ground will leave you with just your double jump.
When holding jump upwards momentum is applied for 0.25 seconds or until the player lets go of the jump button.
you can gain second jump by connecting grapple to a wall,connecting golden hook to someone, or being hit by bomb shockwave.



jump height -359.50
wall jumps seem to increase this number

values
jump strength: 2976
    - maybe monitor on walls, didn't see a difference doing a fast check but might flicker values
initialJumpVelocity
    - fuck knows what this does, changing it doesn't seem to affect much
    - setting the y to -500 seemd to keep jump velocity variable at 500 but didn't seem to visibly affect the jump
jumpVelocity
    - it seems to reach a max of 359.50 unless jumping off a wall where i saw it get up to atleast 600