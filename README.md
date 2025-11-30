# Computer-Vision-Powered-Search-Application
A powerful Streamlit-based application that uses YOLOv11 object detection to scan image datasets and perform AI-powered search across thousands of images.  

This project allows you to:  
    1) Detect objects using YOLOv11  
    2) Save metadata with class counts & bounding boxes  
    3) Search images using AND/OR logic  
    4) Apply optional count thresholds  
    5) View results in a modern grid UI  
    6) Export matching results as JSON  

## 🚀 Features
### 1️⃣ YOLOv11 Object Detection
    1) Runs inference on entire folders
    2) Configurable confidence threshold
    3) Saves annotated images
    4) Metadata stored automatically

### 2️⃣ Intelligent Image Search
    1) OR logic → images with ANY of selected classes
    2) AND logic → images with ALL selected classes
    3) Count thresholds → e.g., person ≤ 3
    4) Highlighting matched classes
    5) Bounding box toggle

## 📁 Project Structure

Computer-Vision-Powered-Search-Application/  
│  
├── app.py  
├── src/  
│   ├── inference.py  
│   ├── utils.py  
│   ├── config.py  
│  
├── configs/  
│   └── default.yaml  
│  
├── processed/  
├── requirements.txt  
└── README.md  

### Dataset Link: https://drive.google.com/drive/folders/1j4L81S0ApFYqpCfwJUK0t2m8AjmxDnHQ?usp=sharing

## ▶️ Run the Application
###Install dependencies:
```
pip install -r requirements.txt
```

### Run Streamlit:
```
streamlit run app.py
```

## 🛠 Tech Stack

| Component        | Technology            |
| ---------------- | --------------------- |
| Object Detection | YOLOv11 (Ultralytics) |
| Web UI           | Streamlit             |
| Image Processing | PIL                   |
| Metadata         | JSON                  |
| Settings         | YAML                  |
| Utilities        | Python                |

## Output

<img width="1909" height="909" alt="image" src="https://github.com/user-attachments/assets/d31d5a01-0744-4d22-bf95-4132b95e84fd" />

<img width="1914" height="924" alt="image" src="https://github.com/user-attachments/assets/4b13bf57-b8d0-4c7d-8dcd-3fbbba3300a2" />

<img width="1918" height="930" alt="image" src="https://github.com/user-attachments/assets/5994e470-fcb3-4134-918c-d89129f5703b" />


## 🙌 Author
Developed by Uddandi Koti Sai Sankar
