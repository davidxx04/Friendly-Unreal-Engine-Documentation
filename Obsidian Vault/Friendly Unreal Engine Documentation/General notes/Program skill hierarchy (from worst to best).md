## 1. Raw programming
Hard coding, repeating code, declaring directly, casting unnecessarily...

## 2. [[Interface|Interfaces]]
Use a interface to group functionality / systems and evade repeating code, multiple ifs etc.


## 3. [[blueprint component]]
Use them to separate between an actor logic and a system logic that actor implements, to evade repeating code and in general to make it more modular and easy to escale.

## 4. Observer pattern
Use the event dispatcher subscription system, where you call (activate) and event where ever you want, and the elements that are subscribed to that element will do something by the moment it gets activated (called).
Best pattern in UE, using this combined with [[blueprint component|bp components]] and interfaces make the perfect mix for a clean, modular and escalable code.  


## 5. C++
Some things are better to be programmed in c++, it is sometimes more clean, more efficient and easier to program things like logic or specific compositions.

## 6. [[Bind my own functions to game functions|Bind functions (c++)]]
Make a UFUNCTION in c++ and then it to a UE default function (like "on component begin overlap"), converting this to the function you have created

## 7. BlueprintNativeEvent (c++)
Make a UFUNCTION in c++, then bind it and lastly make it a BlueprintNativeEvent, converting your function to an implementation. This way you implemented function becomes the default function if you call it in the event graph but you can also use the default implementation, and you can then add more implementation in blueprints, so you are doing a code that it c++ and blueprint friendly, making them friends forever and being a huge programmer.