You map [[Input action]]s choosing the keyboard key or that stuff.

You can access to it from the Get player controller function, so you can assign the map to a [[Character BP]] for example.

It has modifiers:
	-Swizzle: invert the array order (1,0) to (0,1) so you can point to Y axis
	-Negate: put a -. (-1,0)


It´s basically useful for making different input systems (like a player one, and a menu one, both of them using the same buttons) then you can make it more modular and is way comfortable to use.
