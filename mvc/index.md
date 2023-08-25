Pattern #8: Model-View-Controller (MVC)
involves separating an applications’ data model, presentation layer, and control aspects. Following are its’ characteristics:
There are three building blocks here, namely, model, view, and controller.
The application data resides in the model.
Users see the application data through the view, however, the view can’t influence what the user will do with the data.
The controller is the building block between the model and the view. View triggers events, subsequently, the controller acts on it. The action is typically a method call to the model. The response is shown in the view.
Using this model expedites the development.
Development teams can present multiple views to users.
Changes to the UI is common in web applications, however, the MVC pattern doesn’t need changes for it.
The model doesn’t format data before presenting to users, therefore, you can use this pattern with any interface.
There are also a few disadvantages, for e.g.:

With this pattern, the code has new layers, making it harder to navigate the code.
There is typically a learning curve for this pattern, and developers need to know multiple technologies.
Model: The  contains all the data logic
View: The frontend or graphical user interface (GUI)
Controller: The brains of the application that controls how data is displayed