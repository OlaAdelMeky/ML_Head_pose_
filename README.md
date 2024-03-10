### The Head Pose Estimation project 
utilizes the MediaPipe FaceMesh library and Support Vector Regression (SVR) models to predict the pitch, yaw, and roll angles of a person's head based on facial landmarks detected in images. This project aims to provide a robust and accurate method for estimating head orientation, which has applications in various fields, including human-computer interaction, gaming, and virtual reality.

![Project Logo](https://miro.medium.com/v2/resize:fit:604/format:webp/0*3aYfZkNKTeobv07d.png)


## Demo:
https://youtu.be/SMhI2TeI3RY?feature=shared

https://github.com/OlaAdelMeky/ML_Head_pose_/assets/113214668/d5556f07-054c-4d2a-84dd-d113e8e7859a

https://github.com/OlaAdelMeky/ML_Head_pose_/assets/113214668/5c0d723d-cc80-4846-bde7-770989741353

## Key Features:

Facial Landmark Detection: The project leverages the MediaPipe FaceMesh library to detect facial landmarks in images, including key points on the face such as the nose, eyes, and mouth.

Support Vector Regression (SVR): SVR models are employed to predict head pose angles using the extracted facial landmarks. The SVR models are trained on a dataset containing images and corresponding head pose angles.

## Usage:

Installation: Clone the repository and install the required dependencies using the provided instructions.

Run the Script: Execute the head_pose_estimation.py script to process images, detect facial landmarks, and predict head pose angles using the trained SVR models.


## Dependencies:

- Python 3.x
- OpenCV
- NumPy
- Mediapipe
- SciPy
- Scikit-learn
  
## Dataset:  
For this project, the dataset used is <a href=http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip>AFLW2000 Dataset</a>, which consists of 2000 face images, with some information about them like the facial landmarks and the pitch, yaw, and roll values for each picture.

## Conclusion:

The Head Pose Estimation Project provides a valuable tool for estimating head pose angles from facial landmarks, offering potential applications in areas such as human-computer interaction, gaming, and virtual reality. The modular structure and use of machine learning techniques make it accessible for customization and extension based on specific requirements.

## Image for choosing landmarks
![Project Logo](https://github.com/HotaruK/mediapipe_demo/blob/main/keypoints/face_mesh_no.jpg?raw=true)

