You can create functions and stuff and use them in every actor that you want, that´s why it is called component.

It is used to separate between actor logics and another system logic that this actor implements (e.g an interaction system, where we would use a BPC_Interactable). It is also useful if you want to implement the same system in different actors, so it saves you from repeating code.

In general makes your code more modular, reciclable and escalable.

You can help yourself with an [[Interface]] to declare the functions there, and develop them inside the blueprint component, so you have a fantastic modular, clean and beautiful code.