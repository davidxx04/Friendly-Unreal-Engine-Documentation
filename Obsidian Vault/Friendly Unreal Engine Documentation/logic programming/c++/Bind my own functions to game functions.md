Sometimes we don´t want to create a function from scratch, moreover if it is already created by the game. For example the actorBeginOverlap function will be a nightmare to create.
But if we want to do X or Y when that happens, then we can bind and attachment to the funcion, then, the function that we create will be called when the actorBeginOverlap is triggered, for example.

So, to do that we use what is called .AddDynamic. Here is an example:
![[Pasted image 20250828195417.png]]
That is useful to be done in the constructor of our BP.cpp

Then, if you want you can convert this function to an implementation and use the UFUNCTION BlueprintNativeEvent, this way you give the original function a c++ program that you can reprogram in blueprint whenever you want, so useful for base clases (Weapon, Interactable...)