# Face-Recognition-Attendance-Management-System
Attendance Management System based on Face Recognition using Python  and OpenCv  

### Sourcerer
![resume photo](https://github.com/NeerajGupta35483/Face-Recognition-Attendance-System/assets/94775411/4eabfe2c-e287-47b5-b965-a7e2be857918)


### Code Requirements
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

### What steps you have to follow??
- Download my Repository 
- Create a `TrainingImage` folder in a project.
- Open a `AMS_Run.py` and change the all paths with your system path
- Run `AMS_Run.py`.

### Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your faces, it save a images in `TrainingImage` folder
- After that we need to train a model(for train a model click on `Train Image` button.
- It will take 5-10 minutes for training(for 10 person data).
- After training click on `Automatic Attendance` ,it can fill attendance by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database.

### Screenshots

### Basic UI

![Screenshot (1)](https://github.com/NeerajGupta35483/Face-Recognition-Attendance-System/assets/94775411/10221791-edc4-452b-b3c2-49419dc95e90)

### When it Recognises me
![Screenshot (10)](https://github.com/NeerajGupta35483/Face-Recognition-Attendance-System/assets/94775411/2321e489-bc5c-4f59-b6da-983084928406)

### While filling automatic attendance

![Screenshot (4)](https://github.com/NeerajGupta35483/Face-Recognition-Attendance-System/assets/94775411/5616eaec-a6ad-400a-9cb0-399d3cd74a47)

### Manually attendance filling UI

![Screenshot (7)](https://github.com/NeerajGupta35483/Face-Recognition-Attendance-System/assets/94775411/95faee3b-f868-4317-9d56-e5a5b2156322)

### Video demo

[Youtube](https://youtu.be/onms2KDOTtY)


### Notes
- It will require high processing power(I have 8 GB RAM)
- Noisy image can reduce the accuracy, so quality of images should be good.


