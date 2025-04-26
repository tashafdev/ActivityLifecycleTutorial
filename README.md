# ActivityLifecycleTutorial

This project demonstrates the complete lifecycle of an Android Activity using Jetpack Compose. It tracks and logs the activity's state through key lifecycle methods such as `onCreate()`, `onStart()`, `onResume()`, `onPause()`, `onStop()`, and `onDestroy()`.
The app displays lifecycle events on the screen and in Logcat for better understanding and debugging.

## Concept
The **Activity Lifecycle** in Android is crucial for managing an app's behavior and performance. Understanding how an activity transitions through different states (such as being created, paused, or destroyed) is vital for building efficient apps.

In this project:
- The **MainActivity** logs the lifecycle events as the activity moves through various states.
- The app handles configuration changes (e.g., screen rotation) and restores state where necessary.
- It demonstrates the importance of saving data in appropriate lifecycle methods to avoid losing user input or app state.

## Features
- Displays activity lifecycle events in real-time.
- Logs lifecycle state changes to Logcat.
- Handles configuration changes (e.g., screen rotation) and restores the UI state.

## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/tashafdev/ActivityLifecycleTutorial.git
    ```

2. Open the project in Android Studio.

3. Run the app on a physical device or emulator.

## Usage
- Interact with the UI to trigger lifecycle methods.
- Rotate the screen or navigate to simulate activity recreation.

## Contributing
Feel free to fork the repository and submit pull requests for enhancements or bug fixes.

