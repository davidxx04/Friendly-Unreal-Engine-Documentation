# 1. C++ or BP
First you have to notice which one is better in that specific case. 

### C++
- Core gamplay systems:    like interaction, inventory system, combat...
- Performance-critical code:    Procedural, complex AI trees...
- Replication & networking:   server_ client_...
- Reusable plugins, framework...
- Math heavy

### BP
- Level scripting:    Open doors, trigger cutscenes, simple overlaps...
- UI logic:     widgets, simple animations, HUD updates...
- Rapid iteration & prototyping:    evades recompiling.
- Designer-facing logic:    make code usable for designers easily in bp so they can iterate.





# 2. Modularity and scallability
In general, the best way is to follow the next step, especially if you want to make systems that will be contained in different elements / actors.

### a. Interface
Create an interface so you can do the pack that contains all the functions with the respective input and output variables that the system will contain.

### b. BP component
Create a component so it can be added individually to every single bp, then it will be easier for you to evade spaguetti, things interconnect impossible to debug and so on, making it more escalable and modular.

### c. Observer pattern
This is fantastic, when something important happens anywhere, you just call an event dispatcher, and then when you program another thing you decide if you want this other thing to be subscribed to that event so it will be trigger when the event is called, then nothing depends on nothing, nothing is forcely connected to anything, everything is clean.