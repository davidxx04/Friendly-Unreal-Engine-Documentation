The godot signals, sends a signal that triggers code in other actors that are subscribe to that signal.

You can also add inputs to the event so depending on that value, the subscribed person can do one thing or other.

You can for example make a [[blueprint component]], and create the event dispatchers on it, so you can put it as an [[Actor]] component, that way you can subscribe to any of that component functions. So useful.

![[Pasted image 20250804023147.png]]

![[Pasted image 20250804023202.png]]
(Can be parried is the input) so depending on if it can be parried or not, the actor subscribed will do one thing or other (will parry the attack or just defend from it)
