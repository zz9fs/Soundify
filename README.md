# Soundify: A Personalized Music Streaming App

**Soundify** is a personalized music streaming app built with Kotlin and Android Jetpack libraries. It provides an intuitive and immersive music streaming experience, including features such as seamless navigation, a favorites list with offline access, and reliable music playback powered by Google ExoPlayer. The project follows a modern Android development architecture, incorporating key technologies such as MVVM, Dependency Injection with Hilt, and local data storage with Room Database.

## Features
- **Intuitive Navigation**: Implemented Bottom Navigation with Jetpack's Navigation Component to handle seamless transitions between different screens, each represented as a fragment.
- **Personalized Feed**: Users can browse through albums and curated music lists with an easy-to-use interface built using Jetpack Compose.
- **Favorites List**: Users can add songs and albums to a favorites list, which is stored locally using Room Database, allowing offline access to their favorite music.
- **Reliable Music Playback**: Integrated Google ExoPlayer for smooth and reliable playback of audio files, ensuring a high-quality user experience.
- **Simulated Backend**: Utilized `json-server` to simulate backend services for handling network requests through Retrofit.
- **MVVM Architecture**: Adhered to the Model-View-ViewModel (MVVM) architecture for cleaner code separation and better testability.

## Tech Stack
- **Kotlin**: The primary language used to build the app, offering advantages such as null-safety, data classes, and coroutines for efficient concurrency management.
- **Jetpack Compose**: Created responsive and modern UI components using Jetpack Compose.
- **Navigation Component**: Used Jetpack's Navigation framework to manage app navigation through a `NavHost` and navigation graph.
- **Retrofit**: Handled network requests to the simulated backend and data fetching for the app.
- **Room Database**: Provided local data storage for the user's favorite music list, enabling offline access.
- **Google ExoPlayer**: Integrated for handling seamless music playback within the app.
- **Hilt Dependency Injection**: Simplified dependency management and ensured proper lifecycle management of modules within the app.

## Architecture
The app is built using the **MVVM (Model-View-ViewModel)** architecture pattern:
- **Model**: Handles data from the Retrofit network service and Room Database.
- **ViewModel**: Acts as a bridge between the View and Model, providing data to the UI and handling business logic.
- **View**: Represents the UI components built using Jetpack Compose.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Soundify.git
