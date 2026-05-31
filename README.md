# 🌿 AI-Plant-Care (Smart Botanist System)

An AI-powered automated plant care and irrigation system built for Raspberry Pi. It captures real-time plant photos using OpenCV, fetches local 3-day weather data via APIs, and uses the Gemini 2.0 Flash model to analyze plant health, diagnose soil conditions, and dynamically trigger a physical water pump via GPIO pins.

## 🚀 Features
* **Computer Vision:** Automatically flushes the camera buffer to take a live photo of your plant.
* **Smart Context Gathers:** Automatically fetches local weather forecasts and GPS coordinates via IP lookups.
* **AI Analysis:** Leverages `gemini-2.0-flash` to generate a structured botanical health report (Health Score, Soil Status, Diagnosis).
* **Safety First:** Built-in software limits (500ml ceiling) and strict hardware safety shut-offs on script exits to protect your plants.

## 🛠️ Hardware Requirements
* Raspberry Pi (3, 4, or 5)
* USB Web Camera or Pi Camera

## 📦 Core Dependencies
* `google-genai`
* `opencv-python`
* `gpiozero`
* `requests`
