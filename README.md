# GeoQR Navigator

An Android app for scanning QR codes and navigating to geo-locations encoded within them.

## Features

QR Code Scanning: Allows users to scan QR codes using the camera.
Geo-Location Decoding: Parses geo-locations from the QR codes and displays them.
Current Location Tracking: Shows the user's current location.
Distance Calculation: Calculates the distance from the current location to the QR code's geo-location.

## Technologies Used

Android SDK
Google's FusedLocationProviderClient for location services
ZXing ("Zebra Crossing") library for QR code scanning

## Setup and Installation

Clone the repository.
Open the project in Android Studio.
Build and run the application on an Android device or emulator.

## Usage

Press the 'Scan QR Code' button to start scanning.
After scanning a QR code, the app will display the encoded geo-location and calculate the distance from the current location.

## Permissions

Camera: Required for scanning QR codes.
Location: Required for tracking the current location and calculating distances.