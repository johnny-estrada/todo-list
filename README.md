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