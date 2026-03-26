🌟 Affirmations App
An Android app built with Jetpack Compose that displays a scrollable list of daily affirmations paired with beautiful images — designed to bring a little positivity to your day.

✨ Features

📜 Scrollable list of affirmations using Jetpack Compose's LazyColumn
🖼️ Each affirmation is paired with a beautiful, uplifting image
🎨 Clean, modern UI following Material Design principles
⚡ Built entirely in Kotlin with a declarative UI approach

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Architecture:** Single Activity
- **Build System:** Gradle (Kotlin DSL)
- **IDE:** Android Studio
- **Min SDK:** API 21 (Android 5.0 Lollipop)
- 
🚀 Getting Started
Prerequisites

Android Studio (Hedgehog or later recommended)
JDK 11 or higher
Android SDK with API level 21+

Installation

Clone the repository:

bash   git clone https://github.com/RishiJadhav01/Affirmations.git

Open the project in Android Studio.
Let Gradle sync and resolve dependencies.
Run the app on an emulator or a physical device:

Click Run ▶ or press Shift + F10




📁 Project Structure
Affirmations/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/affirmations/
│           │   ├── MainActivity.kt       # Entry point
│           │   ├── model/                # Data models
│           │   └── ui/                   # Composables & UI logic
│           └── res/
│               └── drawable/             # Affirmation images
├── build.gradle.kts
└── settings.gradle.kts
