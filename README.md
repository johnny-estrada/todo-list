# todo-list
Todo list code with MVC architecture

##MVC
Model
*Contains all the code that saves and manages data.

View
*Contains all the code that manages visuals.
*Renders visuals using data in the model.

Controller
*Connects model and view together:
    1. Responds to events from the view (e.g. button clicks)
    2. Tells the model to update its data (and the view to re-render)

MVC allows each section to only do 1 thing.
Allows us to write the minimum amount code.

###MVC allows us to:
  1. You can build bigger and more impressive projects. (For your portfolio that you share with the company)

  2. Most JS frameworks are built on MVC.
        -Provides common function, methods. and objects for rendering visuals and managing data.
        -makes code more consistent

###Local Storage
Saves a string and associates it with a `key`.

``` js
localStorage.setItem('key', 'data');
```

Returns the string
Associated with a `key`

``` js
localStorage.getItem('key');
```
