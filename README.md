# FloodGuard Kerala - Smart Flood Detection & Alert System

FloodGuard Kerala is a simple and interactive web application that simulates real-time flood alerts based on water level sensor input. It is designed to help residents of Kerala monitor potential flood threats in their locality and guide them to the nearest safe shelters.

---

##  Features

- *User Login*: Login with a phone number to access the system.
- *Location Selector*: Choose District, Mandal, and Village to simulate alerts.
- *Water Level Simulator*: Interactive slider mimics real water sensor data.
- *Real-time Alerts*: Displays safety status based on water level thresholds.
- *Audio Alerts*: Plays alert/danger sounds as water level increases.
- *Safe Locations*: Shows nearby shelters for emergency relocation.
- *Zoomable Map*: Interactive Kerala district map for visual context.
- *Mobile Friendly*: Responsive design for easy access on mobile devices.

---
##  How It Works

- The user selects their *district, **mandal, and **village*.
- A *water level simulator* (slider) mimics input from a water level sensor.
- As the level increases:
  - The *gauge fill* updates visually.
  - *Alerts* are triggered depending on danger thresholds.
  - *Sound notifications* play to warn users.
- The app suggests *safe nearby shelters* during high water alerts.

---

# How to Run This Project in VS Code

1. *Clone or Download the Project*  
   Download the files or clone the repository into a folder on your computer.

2. *Open in VS Code*  
   Launch VS Code and open the project folder.

3. *Ensure File Structure*  
   Make sure these files exist in the same folder:
   - index.html
   - styles.css
   - script.js
   - alert.mp3
   - danger.mp3

4. *Use Live Server* (Recommended)
   - Install the *Live Server* extension from VS Code Extensions tab.
   - Right-click on index.html → *"Open with Live Server"*.
   - Your default browser will open the app at http://127.0.0.1:5500/ (or similar).

5. *Without Live Server*
   - Open index.html directly in your browser by double-clicking it.

---

##  Technologies Used

- *HTML5* – Page structure  
- *CSS3* – Styling and layout  
- *JavaScript (Vanilla)* – Logic and simulation  
- *Audio API* – Alert sounds  
- *Responsive Design* – For mobile & desktop support  

---

##  Notes

- This is a *simulation tool* and does not use real sensor data.
- Audio files (alert.mp3 and danger.mp3) must be present in the same folder.
- You can extend this project to use *real IoT sensor data* via APIs for production.

---

##  License

This project is for educational and awareness purposes. All rights reserved © 2025 FloodGuard Kerala.

---

##  Acknowledgments

Special thanks to the people and communities working on disaster awareness and early warning systems in Kerala.
