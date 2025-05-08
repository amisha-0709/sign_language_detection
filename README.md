# 🧠 Sign Language to Text and Speech Converter (Indian Sign Language)

![Sign Language Translation](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Sign_language_ASL.png/800px-Sign_language_ASL.png)

## 📌 Project Overview

This project provides a **real-time translation system for Indian Sign Language (ISL)**, converting hand gestures into both **text** and **speech** using a **webcam**, **machine learning**, and **deep learning (CNN)** models. It bridges communication gaps between the hearing and deaf communities by recognizing ISL gestures and instantly providing readable and audible outputs.

---

## 🎯 Objectives

- Translate ISL hand gestures into real-time text and speech.
- Improve accessibility for the deaf and hard of hearing.
- Provide a user-friendly, intuitive web interface.
- Ensure high accuracy, low latency, and scalability.

---

## 🚀 Features

✅ Real-time webcam-based gesture recognition  
✅ Text and voice output using speech synthesis  
✅ Intuitive UI for ease of use  
✅ Feedback and correction loop for users  
✅ High accuracy using CNN models with Mediapipe landmarks  

---

## 🖥️ Tech Stack

| Category            | Tools/Technologies                      |
|---------------------|-----------------------------------------|
| Programming Language| Python 3.10                             |
| Libraries           | TensorFlow, Keras, OpenCV, cvzone       |
| IDEs                | Jupyter Notebook, VS Code               |
| Frontend            | HTML, CSS, JavaScript                   |
| Model Architecture  | CNN for gesture recognition             |
| Hardware            | Webcam (external/internal), 8GB+ RAM    |

---

SNAPSHOTS
 
FIGURE 8- MEDIA PIPE LANDMARK SYSTEM

![image](https://github.com/user-attachments/assets/6e382d31-0516-455e-9622-df988ce3459d)


We have collected images of different signs of different angles for sign letter A to Z.

![image](https://github.com/user-attachments/assets/1b233bfc-700f-44c7-a1ae-4485896a2a27)

 
FIGURE 9- DATA COLLECTION

Mediapipe Landmark System:

![image](https://github.com/user-attachments/assets/3aca8af7-455d-4978-99cd-8adcce8d9a12)

![image](https://github.com/user-attachments/assets/7e99c554-52b0-4172-ad89-7ce824f2858b)

![image](https://github.com/user-attachments/assets/2db6ab23-dc62-45f0-8e36-7a0f91f9079d)
 
![image](https://github.com/user-attachments/assets/06a89733-56d4-418d-8852-a1b614f12854)
  
![image](https://github.com/user-attachments/assets/aef286b2-4db6-49bd-a948-ec4a36bdd00a)
 
![image](https://github.com/user-attachments/assets/98e3146c-d525-49a4-9521-b3034a24f0d5)

  
Now we get this landmark points and draw it in plain white background using opencv libray

![image](https://github.com/user-attachments/assets/a06a8954-0047-42ff-937e-eb6b0f391ea2)

![image](https://github.com/user-attachments/assets/a759ee5d-4f1c-4b9f-8489-94fb16c5911b)

![image](https://github.com/user-attachments/assets/89b88292-1e4f-4330-adf3-8f12b03114e8)

Now we get this landmark points and draw it in plain white background using opencv library
-By doing this we tackle the situation of background and lightning conditions because the mediapipe labrary will give us landmark points in any background and mostly in any lightning conditions.



