The most profesional way is the following.

A good, modular and escalable way is by using an [[Interface]] to group functions and variables.

Then, use a [[blueprint component]] to program all functions made in the interface, using that component you can use the functions in every actor, that´s why it is called a component. Here we have to be general (for example, if we want to create a heal function, here we will program what healing always do (adding or subtracting X amount of health).

Last, in every [[Actor]] you will program the exact same functions did in the blueprint component, but here you can specify every single thing that you want to do EXCLUSIVELY on that actor (like playing a specific animation, stopping inputs by some seconds...)

That video explains everything:
https://www.youtube.com/watch?v=o3uFXnNxwKE&list=PLaLFqYhYO88x7RCt9TuyBLXmrOHBXKNd-&index=9&ab_channel=AliElzoheiry

