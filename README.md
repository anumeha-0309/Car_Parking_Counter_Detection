# Car_Parking_Counter_Detection

This project implements a computer vision-based system to monitor parking spaces, count parked vehicles, and detect availability in real time. It uses OpenCV for processing video streams or camera feeds, making it suitable for automated parking management systems.

# Features
**Vehicle Detection:** Detects cars entering and exiting parking spaces.<br>
**Parking Space Monitoring:** Tracks and updates the count of occupied and available spaces.<br>
**Real-Time Processing:** Works with live video feeds or pre-recorded videos.<br>
**Visual Overlays:** Displays parking status and vehicle count directly on the video feed.<br>

# Technology Stack
**Library:** OpenCV for image processing and video frame analysis.<br>
**Techniques:** <br>
Background subtraction for movement detection.<br>
Contour detection to identify vehicles.<br>
Zone mapping for parking space monitoring.<br>
**Languages:** Python for ease of integration and adaptability.<br>

# How It Works 
**Vehicle Detection:** <br>
Processes video frames to detect moving objects (vehicles) using background subtraction or object detection techniques.<br>
**Parking Space Analysis:** <br>
Defines parking zones and tracks vehicles entering or exiting these zones.<br>
Updates the parking count based on zone occupancy.<br>
**Visualization:** <br>
Displays the total number of vehicles and available spaces on the video feed with overlays.<br>

 
