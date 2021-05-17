Alternatively, you would dynamically create an instance of class Human using new as you would for another type, say an int:

```c++
int* pointsToNum = new int; // an integer allocated dynamically
delete pointsToNum; // de-allocating memory when done using

Human* firstWoman = new Human(); // dynamically allocated Human
delete firstWoman; // de-allocating memory
```