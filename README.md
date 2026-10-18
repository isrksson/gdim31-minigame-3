# MG3
## Devlog

1. The default serialized values of floats are 0.0f, ints are 0, bools are '0'/false, and strings are an empty string "". These default values represent empty / false values.
2. The Update method is called every frame by the Unity Engine for us. It is a built-in method and we do not manually call it. 
3. KickWeapon is a CircleCollider2D. When player calls KickWeapon's activate function, it unhides and starts a timer using a Timer object. In Update(), it checks every frame to see if the timer is finished. Once the timer's IsFinished() returns true, it hides the KickWeapon again.


## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
