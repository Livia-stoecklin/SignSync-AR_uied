# Research ASL AR

## Project Description: 3D User Interface for Enhanced Communication with Deaf Individuals Using AR Technology

This project aims to bridge the communication gap between deaf individuals and non-signing (non-ASL users) individuals by utilizing augmented reality (AR) on smartphones. Given the widespread availability and accessibility of smartphones, this solution is designed to provide a tool that is readily available to all users.

Our application helps deaf individuals better understand their conversational partners by translating spoken words into virtual sign language, displayed through AR. This allows the deaf person to view virtual hands signing the sentences in real-time, making communication easier than relying solely on lip-reading or translating foreign languages into ASL.

The system also works in reverse, recognizing sign language gestures made by the deaf user and converting them into text or audio for the hearing person. This two-way functionality enhances mutual understanding and facilitates smoother communication between deaf and hearing individuals, especially in everyday interactions.

Through this innovative 3D user interface, we aim to create a more inclusive communication tool, offering an improved experience for users with hearing impairments.


# interpretAR Project Structure

## Root Directory

- `.gradle/`
  - Contains Gradle-specific configurations and caches.
  
- `.idea/`
  - Project-specific settings and configurations for the IntelliJ IDE, including code styles, libraries, and version control settings.
  
- `build/`
  - Output directory for the Gradle build process.
  
- `gradle/`
  - Contains Gradle wrapper files to ensure project builds on different machines without requiring a local Gradle installation.
  
- `libs/`
  - Additional libraries required by the project.
  
- `src/main/`
  - Project source files.

    - `assets/`
      - Static assets used by the app.

    - `java/com/meltdownLabs/interpretAR/`
      - Java code for the app:
        - `AboutUsActivity.java`
        - `CameraPreview.java`
        - `MainActivity.java`
        - `MicrophoneStream.java`
        - `OverlayActivity.java`
        - `TranslatarActivity.java`
        - `UnityPlayerActivity.java`
        - `VocabInfoActivity.java`
    
    - `jniLibs/`
      - Native libraries for specific platforms (e.g., `armeabi-v7a`, `x86`).

    - `res/`
      - Android resources, such as:
        - `drawable/`: Images and other drawable resources.
        - `layout/`: XML layout files.
        - `mipmap/`: App icons for different screen densities.
        - `values/`: String and style resources.
    
    - `AndroidManifest.xml`
      - Defines the app's components, permissions, and metadata.

## Build and Configuration Files

- `build.gradle`
  - Gradle build configuration for the project.
  
- `gradle.properties`
  - Project-wide Gradle properties.
  
- `gradlew`, `gradlew.bat`
  - Gradle wrapper scripts to run Gradle without local installation.
  
- `interpretAR.iml`
  - IntelliJ IDEA module file.
  
- `local.properties`
  - Local configurations (e.g., SDK location).
  
- `proguard-unity.txt`
  - Proguard configuration file for Unity integration.

## Unity Integration

- `interpretAR_Unity/`
  - Contains Unity-specific assets and configurations.
