To make an actor reference to a specific actor (for example a button that opens a door) we can´t do it directly in the class code (the event graph) but there, we can create a variable which is a blueprint actor (for exampe a BP_Door) and make it public (pressing the eye). Then, in the unreal editor we will see if we click our button actor, the variable that we have created in the right displayer of the editor, there we can use the dropper to select a specific door for that specific button actor that we have selected, and that´s all, then that actor will work with the logic that we have implemented in the event graph with that variable, that, in this specific button, is this specific door. Intuitive and cool.


In the following image, we can see the button selected, and at the right displayer, we can see the variable "Door Ref" that we have pointed to the middle BP_Door, so the button will open that door specifically. 
![[Pasted image 20250811182200.png]]
