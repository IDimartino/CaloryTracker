# Calory Tracker App

A simple Calory Tracker app built with modern Android development practices, including Clean Architecture, Multimodule structure, Room for local storage, Retrofit for network calls, Jetpack Compose for UI, and MVVM architecture.

## Features

- Track daily calorie intake.
- Add meals and their nutritional values.
- User-friendly interface built with Jetpack Compose.
- Efficient local data storage with Room.
- Remote data handling via Retrofit.

## Architecture

The app follows **Clean Architecture** principles, with a **Multimodule** setup to ensure scalability and maintainability. The app is structured as follows:

- **Data Layer**: Handles remote and local data operations. Uses **Room** for local database management and **Retrofit** for API calls.
- **Domain Layer**: Contains business logic and interacts with the data layer.
- **Presentation Layer**: Uses **MVVM** to separate UI from business logic. **Jetpack Compose** is used for building the UI.

### Modules

**app**, **core**, **core-ui**, **onboarding**, **tracker**.

## Technologies Used

- **Clean Architecture**: Promotes separation of concerns and testability.
- **Multimodule**: Splits the app into separate modules for better maintainability and modularity.
- **Room**: Local database for storing meals and calorie intake.
- **Retrofit**: For network communication and interacting with external APIs.
- **Jetpack Compose**: Modern UI toolkit for building the user interface.
- **MVVM**: Architecture for organizing code and ensuring clear separation between UI and business logic.
