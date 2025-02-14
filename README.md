# 🚗💤 AI-Powered Driver Drowsiness and Yawning Detection

## 📌 Overview
Drowsy driving is a major cause of road accidents globally. This project introduces a **real-time driver drowsiness detection system** using **computer vision and deep learning** to identify different driver states:
- **Drowsy**
- **Non-Drowsy**
- **Yawn**
- **No Yawn**

The system leverages **Eye Aspect Ratio (EAR)** and **Mouth Aspect Ratio (MAR)** for precise classification and alerts drivers to prevent accidents. 

📄 **Read our full research paper here:**  
🔗 [AI-Powered Drowsiness and Yawning Detection for Proactive Driver Safety](https://www.researchgate.net/publication/387274245_AI-Powered_Drowsiness_and_Yawning_Detection_for_Proactive_Driver_Safety)

---

## 📂 Project Structure
- **`notebooks/`** - Contains the main Jupyter Notebook (`drowsiness_detection.ipynb`) with complete code.
- **`data/`** - Input video, Trained deep learning model (`.h5` file), generated output (`.csv`), and face detection model (`.dat`).
- **`docs/`** - Setup instructions, requirements, and documentation.

---
## 🔗 Download Models
Due to file size limitations, download models manually from:
👉 [face_detection.dat](https://drive.google.com/file/d/1-4MOU44SB_KR_6p8sMrJ_YBw6Q7_7bG-/view?usp=sharing)
👉 [`drowsiness_detection_model_new.h5` file](https://drive.google.com/file/d/1KNuDh0oBYKIdmXhsl760UC79dnIdW4ej/view?usp=drive_link)

## 🔧 Setup & Installation
To get started, clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/DrowsinessDetection.git
cd DrowsinessDetection
pip install -r docs/requirements.txt
