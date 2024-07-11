# SmartCheckIn - Attendance System using Flask and OpenCV

This is a face recognition attendance system built using Flask and OpenCV libraries of Python. It captures images through the webcam, extracts faces from the image using Haar Cascade Classifier, and identifies the face using a pre-trained K-Nearest Neighbors (KNN) classifier model. The identified user is then marked present in the attendance record.

## **Requirements**

- Python 3.x
- Flask
- OpenCV
- NumPy
- scikit-learn

## **Installation**

1. Clone the repository to your local machine:

```
git clone https://github.com/Kiransala/Smart-Check-In-Attendance-System.git
```

2. Install the required libraries.

3. Run the Flask app:

```
python app.py
```

## **Usage**

The home page of the application will show the attendance records of the current date, and the total number of registered users. To take attendance, click on the 'Take Attendance' button.

The first time you take attendance, the app will ask you to add a new user. Enter the user's name and ID, and upload a clear image of their face. The app will use this image to train the KNN model.

Once you have added a new user, you can take attendance by clicking on the 'Take Attendance' button. The app will open your webcam and show your face on the screen. If your face is recognized, your name and ID will be displayed on the screen, and you will be marked present in the attendance record.

The attendance records for the current date can be found in the 'Attendance' folder, with the filename 'Attendance_dd-mm-yy.csv'. The records are stored in a CSV format, with the columns 'Name', 'Roll', and 'Time'.

## **Contributing**

Contributions to this project are always welcome. If you want to contribute, please fork the repository, create a new branch, and submit a pull request.
