# Car_Parking_Counter_Detection

# This project implements a computer vision-based system to monitor parking spaces, count parked vehicles, and detect availability in real time. It uses OpenCV for processing video streams or camera feeds, making it suitable for automated parking management systems.

# Features
**Vehicle Detection:** Detects cars entering and exiting parking spaces.
**Parking Space Monitoring:** Tracks and updates the count of occupied and available spaces.
**Real-Time Processing:** Works with live video feeds or pre-recorded videos.
**Visual Overlays:** Displays parking status and vehicle count directly on the video feed.

# Technology Stack
**Library:** OpenCV for image processing and video frame analysis.
**Techniques:**
Background subtraction for movement detection.
Contour detection to identify vehicles.
Zone mapping for parking space monitoring.
**Languages:** Python for ease of integration and adaptability.

# How It Works
**Vehicle Detection:** Processes video frames to detect moving objects (vehicles) using background subtraction or object detection techniques.
**Parking Space Analysis:** 
Defines parking zones and tracks vehicles entering or exiting these zones.
Updates the parking count based on zone occupancy.
**Visualization:**
Displays the total number of vehicles and available spaces on the video feed with overlays.

 
