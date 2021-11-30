When creating a variable in a script, you can declare it to be `public`. 

--- code ---
---
language: cs
---
public float patrolSpeed = 0.0f; // default value if not set in Inspector
--- /code ---

This means that the variable will appear in the script component in the Inspector window. 

You can use the public variable during playmode to experiment with settings such as move and spin speed. Remember any changes you make in playmode will be lost when you exit playmode so take a note of your favourite values. 

Multiple GameObjects can use the same Script and set different values in the Inspector for public variables. 

**Tip:** Be careful when setting public variables in the Inspector window as this will override values set in your script. 

You can create many types of public variable such as `GameObject` variables so that you can access GameObjects from the scene:

--- code ---
---
language: cs
---
public GameObject player;
--- /code ---
