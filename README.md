# Interactive-Map-using-Computer-Vision

This project creates an interactive map application that captures the world map using Iriun Webcam, identifies the corner points of the map, extracts country polygons, and displays country names. Additionally, it estimates and displays flight times between India and each country on the map.

The interactive map project utilizes computer vision techniques to enable real-time interaction with a physical map captured via a webcam. By recognizing and processing the map, the application identifies countries and provides estimated flight times between India and other countries.

Features
Capture the World Map:
The map is captured using the Iriun Webcam, which allows for live streaming of the map into the application.
Detect Corner Points of the Map:
The application identifies and processes the four corner points of the map to align and calibrate the map's geometry.
Extract Country Polygons:
The system extracts polygonal representations of countries from the map image.
Display Country Names:
Recognizes and overlays country names onto the map.
Estimate and Display Flight Times:
Calculates and displays the estimated flight times from India to each country on the map.

Setup
Prerequisites
Python 3.x
OpenCV
Mediapipe
NumPy
Iriun Webcam software (for capturing the map)
