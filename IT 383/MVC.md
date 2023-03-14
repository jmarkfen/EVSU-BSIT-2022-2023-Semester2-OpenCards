## A software design pattern which separates concerns of an application into the model, view, and controller

Model-View-Controller (MVC) pattern

## Benefits of using MVC frameworks

- separation of concerns
- reusability
- scalability
- maintainability
- community support
- security

## Alternatives to MVC

- Model-View-Presenter (MVP)
- Model-View-ViewModel (MVVM)
- Hierarchical Model-View-Controller (HMVC)
- Frontend-centric architectures
- Domain-driven design (DDD)

## In the MVC pattern, it is responsible for managing the application's data and business logic.

Model

## In the MVC pattern, it interacts with the database and other data sources to retrieve and store data.

Model

## In the MVC pattern, it contains validation and processing logic for manipulating data.

Model

## In the MVC pattern, it acts as the backend and handles all data-related operations.

Model

## In the MVC pattern, it is responsible for presenting the user interface to the user.

View

## In the MVC pattern, it serves as the frontend and handles all user interface-relation operations. 

View

## In the MVC pattern, it sends input to the controller for processing. 

View

## In the MVC pattern, it is responsible for managing user requests and coordinating the Model and View.

Controller

## In the MVC pattern, it receives input from the View and processes it according to the Model.

Controller

## In the MVC pattern, it serves as the mediator between the Model and View.

Controller

## In the MVC pattern, it is responsible for updating the View with the latest data from the Model.

Controller

## Flow of data in MVC pattern

- User interacts through the View, which then sends input to the Controller
- Controller receives input, then communicates with Model to retrieve or store data
- Model retrieves/stores data, then returns the result to the Controller
- Controller updates the View with data from the Model
- View receives data from Controller, formats it, then shows it to the user

## tldr; Flow of data in MVC pattern

- user request to controller through view
- controller contacts model
- model queries database
- model returns result to controller
- controller delives data to view
- view shows information to user