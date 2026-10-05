# Android Application – Activity Life Cycle & Basic UI

## Aim

Create an Android application to demonstrate **Activity Life Cycle and Basic UI**.

## Description

This practical demonstrates the basic structure of an Android application along with the **Activity Life Cycle**. The application displays a **Hello World** message using a TextView and demonstrates different lifecycle methods through Logcat and Toast messages.

## Features

* Simple Android user interface
* Hello World TextView
* Yellow background with styled text
* Activity Life Cycle demonstration
* Logcat messages for lifecycle events
* Toast messages for user notification
* ConstraintLayout-based UI

## Basic UI

The application contains a centered **TextView** with:

* **Text:** Hello World
* **Background:** Yellow (`#FFFF00`)
* **Text Color:** Holo Blue
* **Text Size:** 27sp
* **Style:** Bold + Italic
* **Layout:** ConstraintLayout

## Activity Life Cycle

The following lifecycle methods are implemented:

1. `onCreate()` – Called when the Activity is created.
2. `onStart()` – Activity becomes visible.
3. `onResume()` – Activity comes into the foreground.
4. `onPause()` – Activity is partially interrupted.
5. `onStop()` – Activity is no longer visible.
6. `onRestart()` – Called when the Activity is restarted.
7. `onDestroy()` – Activity is removed from memory.

## Messages Used

Each lifecycle method calls the `display()` function, which shows:

* **Logcat message** using `Log.i()`
* **Toast message** using `Toast.makeText()`

## Project Structure

```text
app/
├── java/
│   └── MainActivity.kt
├── res/
│   └── layout/
│       └── main_activity.xml
└── AndroidManifest.xml
```

## Android Components Used

* Activity
* TextView
* ConstraintLayout
* Toast
* Logcat
* AndroidManifest.xml

## Working

When the application starts, `onCreate()` is called first. As the user interacts with the application or changes its state, different lifecycle methods are triggered. Each method displays its name in **Logcat** and through a **Toast message**, making the Activity Life Cycle easy to observe.

<img width="300" height="700" alt="image" src="https://github.com/user-attachments/assets/b64b65d9-2dd5-4bd1-94e9-3d2090d5c376" />
<img width="300" height="700" alt="image" src="https://github.com/user-attachments/assets/10ec9803-c1c7-47f3-be7d-cc1bcc5c3d99" />
<img width="300" height="700" alt="image" src="https://github.com/user-attachments/assets/b00e239d-6ed5-403a-9b6a-835cf8c91508" />
<img width="300" height="700" alt="image" src="https://github.com/user-attachments/assets/f950f7fd-ba99-4b0a-b7b4-08d4689b975e" />
<img width="300" height="700" alt="image" src="https://github.com/user-attachments/assets/1769ba9c-34db-4d8e-834d-a127f3b98e79" />
<img width="300" height="700" alt="image" src="https://github.com/user-attachments/assets/153b7559-245a-4036-b95f-03595f84890f" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/7a544c97-08ff-4ceb-9236-69a91d5a23b4" />


## Conclusion

This practical provides an understanding of the **Android Activity Life Cycle** and demonstrates how to create a simple user interface using **ConstraintLayout and TextView**. It also shows how lifecycle events can be monitored using Logcat and Toast messages.
