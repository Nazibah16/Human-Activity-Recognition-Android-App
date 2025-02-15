# Human-Activity-Recognition-Android-App
This Android application utilizes smartphone sensors to recognize various human activities and collects data for analysis.  It identifies activities such as Walking, Jogging, Running, Sitting, Climbing Up, Climbing Down, and Traveling.  The app also collects user demographics, specifically gender and age category.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data Collection](#data-collection)
- [Setup](#setup)

## Introduction
This project aims to develop a robust Human Activity Recognition (HAR) system using the built-in sensors of an Android smartphone.  By analyzing sensor data such as accelerometer, gyroscope, gps, orientation sensor and light sensor , the app can accurately classify different physical activities.  The collected data, along with user demographics, can be used for various purposes, including health monitoring, fitness tracking, and personalized recommendations.

## Features
* Real-time Activity Recognition:  Identifies the following activities in real-time:
    * Walking
    * Jogging
    * Running
    * Sitting
    * Climbing Up
    * Climbing Down
    * Traveling 
* Data Collection: Gathers sensor data (e.g., accelerometer, gyroscope, gps, orientation and light sensor) associated with each recognized activity.
* User Demographics: Collects user's gender and age category.
* Firebase Integration:  Utilizes Firebase for data storage.
* Android Studio & Kotlin: Developed using Android Studio with the Kotlin programming language.

## Technologies Used
* Android Studio: The primary IDE for Android development.
* Kotlin: The programming language used for the app.
* XML: Used for designing the user interface layouts.
* Firebase:  For saving and collecting realtime data, Firebase realtime database is used.
* Sensors: Accelerometer, Gyroscope, GPS, orientation and light sensor.
* Other Libraries/SDKs: Android SDK Platform 35, Android SDK Platform 34, Sources for Android 34, Android TiramisuPrivacySandbox Preview.

## Data Collection
The app collects data from various sensors on the Android phone, including:
* Accelerometer: Measures acceleration forces.
* Gyroscope: Measures angular velocity.
* GPS: For location tracking.
* Light sensor: To measure the sensibility of light.
* Orientation sensor: Describes the device's physical orientation in relation to 3-Dimensional cartesian coordinate system.

The collected data is associated with the recognized activity and the user's gender and age category. Data is stored securely using Firebase.

## Setup
1. Open in Android Studio: Open the project in Android Studio.
2. Firebase Setup: Configure Firebase for the project.  Replace the placeholder Firebase configuration details with your own.
3. Dependencies: Ensure all dependencies are installed.  Check the build.gradle files for required dependencies.
4. Build and Run: Build the project and run it on an Android emulator or physical device.
