You group a list of functions (that will be contained in a system, like a damage system, which always contains at least the take damage function and some getters). And you indicate the input and ouput of them, helping yourself with structs (which can contain enums) and that staff.

It helps you not to forget some functions when adding a system to some actor.
It also helps if you have to detect some different objects allowing you to detect if they are implementing the interface (by the "does object implement interface" BP block) instead of doing 1000 ifs.

If you want more modularity, you can help yourself with a [[blueprint component]] where you can program the interface functions (individually from the interface), so every actor can program a specific function of the interface with different changes, and the general logic is in the component.

![[Pasted image 20250808024616.png]]

We declare the interface:
![[Pasted image 20250808024646.png]]

Then we program the [[blueprint component]] (individually to the interface):
![[Pasted image 20250808024724.png]]

Last we attach our actor with the interface and in the functions, we attach the [[blueprint component]] so we call the component function in the actor function and then add whatever we want that makes that actor function different from the other actors one:
![[Pasted image 20250808025141.png]]
