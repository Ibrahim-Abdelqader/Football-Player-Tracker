# Football Player Tracker

<img src="https://github.com/user-attachments/assets/18e61c5d-1ed7-43fc-ac02-25d755d950ef" width="400"/>
<img src="https://github.com/user-attachments/assets/2297465f-b3dc-4200-8d14-ee6101f804f0" width="400"/>
<img src="https://github.com/user-attachments/assets/c8f78744-44f8-48b0-abc3-8b635d964b94" width="400"/>
<img src="https://github.com/user-attachments/assets/f5066773-0275-45e7-b29c-32a8fdc2b041" width="400"/> 

## Overview
A machine learning-powered application for tracking football players in video using YOLO model

--- 

## 📌 Table of Contents
| Section                | Description |
|------------------------|-------------|
| [📽️ Video](#-video) | tryint to run the project |
| [✨ Features](#-features) | Key capabilities of the project |
| [🔃 Installation](#-installation) | Steps to set up and install dependencies |
| [🛠️ Key Functionalities](#-key-functionalities) | Core operations the project performs |
| [🪄 Usage](#-usage) | How to run and use the application |
| [📝 Configuration Notes](#-configuration-notes) | Customization options for tracking and heatmaps |
| [⚠️ Limitation](#-limitation) | Constraints and considerations |
| [🤝 Contributions](#-contributions) | How to contribute to the project |
| [📜 License](#-license) | Licensing information |

---

## 📽️ Video
https://github.com/user-attachments/assets/3803af15-b498-4fc9-a011-8991e0f85e3c

---

## ✨ Features
- Real-time player tracking
- Player ID assignment
- Heatmap generation
- single/multi-player view modes
- Video analysis with machine learning

---

## 🔃 Installation
1. Prerequisites
   ```bash 
   Python 3.8+ | pip | Torch-compatible GPU
   ```
2. Install Dependencies
   ``` bash
    pip install requriments.txt
   ```
 --- 

 ## 🛠️ Key Functionalities
- Load and process football match videos
- Track individual players
- Generate movement heatmaps
- Visualize player positions
- Zoom view for single player tracking

---

## 🪄 Usage
1. Launch application
   ``` bash
   python yolo.py
   ```
2. Basic workflow
   - Click 📂 Load Video to select a video file
   - Press ▶ Start Tracking to begin analysis
   - Select player ID from dropdown for individual tracking
   - Use 🔄 Toggle Single Player to switch views
   - Generate heatmaps with 🌡 Generate Heatmap

---

## 📝 Configuration Notes
- Field Dimensions: Adjust `self.field_width` and `self.field_height` in code for different stadium sizes
- Tracking Sensitivity: Modify `self.inactive_timeout` and distance threshold in `assign_player_id()`
- Heatmap Customization: Edit `generate_heatmap()` for color/transparency changes

---

## ⚠️ Limitation
- Designed for wide-angle footage of football fields
- Player identification accuracy decreases with heavy occlusion
- Heatmap coordinates assume fixed camera perspective

---

## 🤝 Contributions
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request with your enhancements.

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact
If you have any questions or suggestions, feel free to reach out via GitHub or email at [Ibrahim.Ibrahim051@eng-st.cu.edu.eg]
