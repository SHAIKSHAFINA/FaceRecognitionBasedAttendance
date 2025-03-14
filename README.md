
# **Face Recognition-Based Attendance Management System**  

🚀 **An advanced attendance tracking system that identifies, verifies, and recognizes individuals using face recognition. It automates the attendance process by marking the time of arrival in a CSV file.**  

## **🌟 Uniqueness of the Project**  
Unlike traditional attendance systems that rely on manual entry, RFID cards, or fingerprint scanners, this system:  
1.**Uses Face Recognition** – No need for ID cards or fingerprints.  
2.**Automates Attendance** – Detects and marks attendance in real-time.  
3.**Prevents Proxy Attendance** – Ensures that only authorized individuals are marked present.  
4.**Stores Time of Arrival** – Records exact timestamps for attendance logs.  

## **🎯 Core Idea**  
The system **identifies, verifies, and recognizes** individuals using a pre-trained face recognition model. It captures an image from a live camera feed, compares it with stored images, and marks attendance in a **CSV file** with timestamps.  

## **🛠️ Tech Stack**  
- **Python** 🐍  
- **OpenCV,Face-Recognition**👁️ (Face Detection & Recognition)  
- **Numpy**📊 (Data Handling)  

## **📂 Project Structure**  
```
📁 AttedanceManagementSystem  
 ├── 📂 AttendanceImgs/        # Images used for face recognition  
 ├── 📂 BasicImgs/             # Reference images for face matching  
 ├── 📜 Attendance.py          # Main script for attendance tracking  
 ├── 📜 Basic.py               # Face recognition script  
 ├── 📜 Attendance.csv         # Attendance log file (stores name & time of arrival)  
 ├── 📂 .idea/                 # IDE settings (can be ignored)  
 ├── README.md                 # Project Documentation  
```

## **🚀 How It Works**  
1. **Face Detection** – Captures faces from a live camera feed.  
2. **Face Recognition** – Matches detected faces with stored images.  
3. **Verification** – Ensures correct identification before marking attendance.  
4. **Attendance Logging** – Saves name & time of arrival in a CSV file.  


## **📊 Example Attendance Record (CSV File Format)**  
| Name      | Time of Arrival     |  
|-----------|--------------------|  
|Safina | 09:05 AM           |  
| Vijaya | 09:10 AM           |  

