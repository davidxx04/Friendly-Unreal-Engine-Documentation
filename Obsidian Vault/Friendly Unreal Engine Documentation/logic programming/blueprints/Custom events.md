The same as [[Event dispatchers]] but they are only inside the actor itself, and he uses its custom events.

These can be used in the [[Construction script]]. You declared them on it so you can use them on the event graph.

![[Pasted image 20250804032259.png]]
The BPC damage system is the [[blueprint component]] that contains some [[Event dispatchers]] that triggers the creation of the create event on here. So you are declaring the custom events Death() and Blocked(CanBeParried) that you can use on the event graph (next image).

![[Pasted image 20250804032636.png]]