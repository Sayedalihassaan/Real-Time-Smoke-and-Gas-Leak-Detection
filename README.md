# 🚨 Real-Time Smoke and Gas Leak Detection 🚨

**A cutting-edge AI-driven solution to ensure safety and prevent fire and gas leak hazards in real-time!**

## 🔥 Project Overview
The **Real-Time Smoke and Gas Leak Detection System** is a powerful tool that leverages advanced deep learning and computer vision techniques to detect dangerous smoke, fire, and gas leaks in real-time. This system uses the YOLOv8 object detection model to analyze video frames and raise alarms instantly upon detecting potential hazards.

The system integrates with **Pygame** for audio alerts, providing both visual and auditory notifications when a fire or gas leak is detected.

## 🎯 Key Features
- **Real-Time Detection**: Detects smoke, fire, and gas leaks from live video feeds.
- **Audio Alerts**: Triggers an alarm sound when fire or gas leaks are detected.
- **Bounding Box and Labels**: Highlights detected objects (fire, smoke) with labeled bounding boxes.
- **Highly Accurate**: Powered by a custom-trained **YOLOv8** model for precise detection.
- **Customizable Alerts**: Easily replace alarm sounds or extend detection capabilities.

## 📽️ Demo
Check out the video demonstration of the system in action:

[![Real-Time Smoke and Gas Leak Detection Demo](link_to_thumbnail)](link_to_video)

## 🛠️ Tech Stack
- **YOLOv8**: Deep learning model for object detection
- **OpenCV**: Real-time computer vision library
- **Pygame**: Python library used for playing alarm sounds
- **cvzone**: Extension of OpenCV for additional computer vision functionalities

## 🚀 How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Real-Time-Smoke-and-Gas-Leak-Detection.git
   ```

2. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the pre-trained YOLOv8 model**:
   - Place your custom-trained YOLOv8 model (`best.pt`) inside the project directory.

4. **Run the detection script**:
   ```bash
   python detect.py
   ```

5. **Ensure your video source (e.g., Fire.mp4) is available in the directory**.

6. **Watch the system detect smoke and gas leaks in real-time and trigger alarms!**

## ⚙️ Requirements
- Python 3.x
- OpenCV
- YOLOv8
- Pygame
- cvzone

## 🔔 Customization
- You can customize the alarm sound by replacing the `alarm.wav` file.
- To modify the detection logic (e.g., adding more classes), update the **YOLOv8** model and the corresponding labels in the `coco1.txt` file.

## 📚 Use Cases
- **Industrial Safety**: Monitor factories and industrial areas for fire and gas leaks.
- **Home Safety**: Implement in homes to detect potential fire hazards.
- **Smart Buildings**: Integration in smart homes and buildings for safety automation.

## 🧠 Future Improvements
- Adding support for more hazardous material detections.
- Integrating with cloud-based monitoring systems for large-scale deployments.
- Adding notifications via SMS or IoT devices.

## 🤝 Contribution
Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/yourusername/Real-Time-Smoke-and-Gas-Leak-Detection/issues).

## 📜 License
This project is licensed under the MIT License.
