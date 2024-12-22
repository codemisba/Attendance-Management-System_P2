# Attendance-Management-System_P2

This project is a Face Recognition-based Attendance System that uses OpenCV, Tkinter, and an SQL database to manage student records and attendance.
The system provides functionalities for adding, updating, deleting student details, training the face recognition model, and marking attendance through face recognition.


***Features***
- Real-time face detection and recognition.
- Attendance marking with timestamps.
- Simple and user-friendly interface.
- Stores attendance records in a CSV file.

***Requirements***
1. Python 3.7 or later
2. Required Libraries:
   - OpenCV
   - NumPy
   - Pandas
3. VS Code (or any preferred Python IDE)

***Installation***
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/attendance-management-system.git
   cd attendance-management-system
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

**TECHNOLOGIES USED** 
1. Python 3.11 (Latest stable version of Python)
2. OpenCV (for face detection and recognition)
3. Tkinter (for creating the GUI)
4. SQL Database (to store student details)
5. CSV (to store attendance)


***How to Run***
1. Open the project in VS Code.
2. Run the following command in the terminal:
   ```bash
   python main.py
   ```
3. Follow the prompts to register faces and mark attendance.

***Project Structure***
```
attendance-management-system/
├── main.py          # Main application script
├── face_recog.py    # Face recognition module
├── data/            # Directory to store facial data
├── attendance.csv   # Attendance log file
└── requirements.txt # List of required libraries
```

***Future Improvements***
- Integrate with a database for better data management.
- Add email notifications for attendance alerts.
- Build a web interface for remote access.

