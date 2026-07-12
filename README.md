# Project-Pulse-X-Android
A Java-based mobile AI assistant to pre-screen chest X-rays for pneumonia.
# 📱 Project Pulse-X: Java-Based Mobile Diagnostic Screening Assistant

Project Pulse-X is an independent mobile healthcare initiative designed to run on portable Android devices. It provides a zero-cost, automated secondary screening layer for childhood pneumonia, optimized for frontline health workers in low-resource environments.

## 🚀 Project Overview
* **Developer:** Independent Research Project (Age 14)
* **Target Architecture:** Java / Android Environment
* **Core Technology:** Computer Vision Image Recognition trained on a verified chest radiograph dataset.

## 🧠 Technical Architecture (`Classifier.java`)
The Java script included in this repository handles the mobile deployment phase of the neural network. It functions by:
1. Receiving an image file input from a mobile device camera or gallery.
2. Normalizing the image pixel values into a flat bitmap array suitable for mobile processors.
3. Running the bitmap through a lightweight TensorFlow Lite / JavaScript runtime engine to deliver instantaneous offline-friendly classification output.

## 🌍 Live Interactive Prototype
Before compiling into a final Android Package (APK), you can interactively test the live web-hosted version of this exact neural network architecture here:
https://teachablemachine.withgoogle.com/models/qvif2QxG7/
