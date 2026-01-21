# 📦 AR Smart Stock Manager  
**Intelligent Stock Management using Augmented Reality & Artificial Intelligence**

## 🧠 Project Description

**AR Smart Stock Manager** is an innovative mobile application that combines:

- 📱 **Augmented Reality (AR)** using **Vuforia Engine**
- 🤖 **Artificial Intelligence (AI)** for product recognition
- ☁️ **Firebase** for real-time stock and product data management
- 🎨 **User-friendly UI** developed with Unity

The application allows users to **scan physical products**, **recognize them using AI**, and **display stock information in AR**, **without using fixed Image Targets**.

---

## 🎯 Project Objectives

- Digitize stock management processes  
- Recognize **previously unknown products**  
- Improve inventory efficiency using AR  
- Provide a scalable and extensible solution  

---

## 🧩 System Architecture

Vuforia Camera
↓
Image Capture (Texture2D)
↓
AI Model (Classification / Detection)
↓
Product Identified
↓
Firebase Database
↓
AR Product Information Panel


---

## 🚀 Key Features

- 📸 Real-time camera image capture  
- 🤖 AI-based product recognition  
- 🏷️ AR display of product information:
  - Product name
  - Quantity
  - Price
  - Stock status
- ☁️ Firebase synchronization  
- 🧱 Stable AR experience without Image Targets  
- 🔄 Easy integration of new products  

---

## 🛠️ Technologies Used

### 🔹 Augmented Reality
- Unity  
- Vuforia Engine  

### 🔹 Artificial Intelligence
- TensorFlow Lite (on-device) **or**
- Firebase ML **or**
- REST API (Python / FastAPI)

### 🔹 Backend & Database
- Firebase Firestore / Realtime Database  
- Firebase Authentication *(optional)*  

### 🔹 UI / UX
- Unity UI  
- Canvas (Screen Space / World Space)

---

## 📱 Supported Platforms

- ✅ Android  
- ⚠️ iOS (configurable with Vuforia)

---

## 📂 Project Structure
AR-Smart-Stock-Manager/
│
├── Assets/
│ ├── Scripts/
│ │ ├── CameraCapture.cs
│ │ ├── AIManager.cs
│ │ ├── FirebaseManager.cs
│ │ └── UIManager.cs
│ │
│ ├── UI/
│ ├── Models/
│ ├── Scenes/
│
├── Packages/
├── ProjectSettings/
└── README.md

---

## 🧪 Recognition Workflow

1. The user points the camera at a product  
2. Presses the **Scan** button  
3. The image is captured  
4. The AI model recognizes the product  
5. Product data is retrieved from Firebase  
6. The **AR Product Panel** is displayed  

---

## 🧠 Why Vuforia without Image Targets?

| AR Foundation | Vuforia + AI |
|--------------|-------------|
| Complex camera pipeline | Simple image capture |
| ARCore-dependent | Platform-independent |
| Rigid tracking | Flexible recognition |
| Difficult AI integration | AI-driven recognition |

> **Vuforia is used only for AR scene stabilization**, while **AI performs 100% of the recognition**.

---

## 📸 Demo

<img width="386" height="631" alt="image" src="https://github.com/user-attachments/assets/93a36ad1-4258-4102-b277-2e969fb91e81" />


## 🔮 Future Improvements

- 🔍 Multi-product detection  
- 📊 Stock analytics dashboard  
- 🧾 Scan history  
- 🧠 Advanced AI models (YOLO / SSD)  
- 🥽 AR Glasses support  

## 👨‍💻 Author

**Youssef Benyahia**  
🎓 Academic / Personal Project  
🌍 Fields: Augmented Reality • Artificial Intelligence • Smart Systems  

---

## 📜 License

This project is licensed under the **MIT License** — free to use for educational and research purposes.
