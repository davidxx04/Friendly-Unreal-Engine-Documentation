It create the functions, but only in block, nothing about programing them, they are programmed in the actor where you use the [[Interface]], the interface is only used to group some functions that everybody who has some functionability will has. For example, if there is a damage system, every actor who is involved in that damage system will necessarily contain:
- a take damage function
- a get max health function
- a get current health function
- a heal function (maybe, but it is a good practice to get it inside the interface beacuase we heal in every single game, and the enemies too)

That´s way we use the interface, to say "okey, this system must have that functions always so lets do a box that contains all of them so we make sure we are not forgetting any when we implement our actors functions"
