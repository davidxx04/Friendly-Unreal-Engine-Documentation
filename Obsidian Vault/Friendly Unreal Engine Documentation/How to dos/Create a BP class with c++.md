Tools > select c++ blabla > actor or whatever.

I find a pattern in the order of how things be placed, and is the next:

### 1. Components
1. Use UPROPERTIES to set the UComponents, 
2. then intialize them in the constructor.

### 2. UPROPERTIES & UFUNCTIONS
First de uproperties (varaibles with properties like visibility) and then ufunctions

### 3. Develop the UFUNCTIONS on the .cpp
Develop the functions, the interesting part
