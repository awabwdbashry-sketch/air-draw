# ✋ Air Draw

**Air Draw** is a real-time virtual drawing application that allows users to draw in the air using their **index finger** in front of a webcam.

The project uses **Computer Vision** techniques with Python, OpenCV, MediaPipe, and NumPy to create an interactive touchless drawing experience without requiring a mouse, touchscreen, or physical drawing tablet.

---

## ✨ Features

* ✋ Real-time hand tracking using a webcam
* ☝️ Use the index finger as a virtual drawing tool
* 🎨 Draw in the air in real time
* 🌈 Color selection toolbar
* 🖌️ Support for multiple drawing colors
* 📹 Live webcam video processing
* 🔍 Hand landmark detection using MediaPipe
* 📍 Real-time index finger position tracking
* ⚡ Real-time drawing and video processing
* 🖥️ Simple and interactive interface
* 🚫 No mouse, drawing tablet, or touchscreen required

---

## 🛠️ Technologies Used

| Technology  | Purpose                      |
| ----------- | ---------------------------- |
| 🐍 Python   | Main programming language    |
| 👁️ OpenCV  | Video and image processing   |
| ✋ MediaPipe | Hand detection and tracking  |
| 🔢 NumPy    | Image and drawing operations |

---

## ⚙️ How It Works

The application starts by accessing the **webcam** and continuously capturing video frames.

**MediaPipe** analyzes each frame to detect the user's hand and its main landmarks.

The application then identifies the position of the **index finger** and uses its coordinates as a virtual drawing point.

As the user moves the index finger in front of the camera, the application tracks the movement and connects the detected positions to create a drawing on the virtual canvas.

A **color toolbar** is also provided, allowing the user to select different colors for drawing.

### 🔄 Processing Pipeline

```text
📹 Webcam
     ↓
🖼️ Video Frame
     ↓
✋ MediaPipe Hand Detection
     ↓
📍 Hand Landmarks
     ↓
☝️ Index Finger Detection
     ↓
📌 Finger Position Tracking
     ↓
🎨 Drawing on Canvas
     ↓
🖥️ Display Result
```

---

## 🎨 Drawing Controls

The main interaction is based on the movement of the index finger:

* ☝️ **Index finger** → Drawing tool
* 🖐️ **Hand movement** → Controls the drawing position
* 🎨 **Color toolbar** → Selects the drawing color
* 📹 **Webcam** → Provides the real-time video input

The user can move the index finger in front of the webcam to create drawings directly on the screen.

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/awabwdbashry-sketch/air-draw.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd air-draw
```

### 3️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 4️⃣ Activate the Virtual Environment

#### 🪟 Windows

```bash
venv\Scripts\activate
```

#### 🐧 Linux / macOS

```bash
source venv/bin/activate
```

### 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📋 Requirements

The project requires:

* 🐍 Python
* 📹 A working webcam
* 📦 The libraries listed in `requirements.txt`

Main dependencies:

```text
opencv-python
mediapipe
numpy
```

---

## ▶️ Usage

After installing all required dependencies, run the main application:

```bash
python air_draw.py
```

The webcam will start and the application will begin detecting the user's hand.

Once the camera is running:

1. ✋ Place your hand in front of the webcam.
2. ☝️ Use your index finger to control the drawing.
3. 🎨 Use the color toolbar to select a color.
4. 🖌️ Move your finger to create the drawing on the screen.

---

## 📁 Project Structure

```text
air-draw/
│
├── air_draw.py
├── README.md
├── README_AR.md
├── requirements.txt
└── .gitignore
```

### 📄 Main File

**`air_draw.py`**

The main file contains the core implementation of the Air Draw application, including:

* 📹 Webcam initialization
* ✋ Hand detection
* 📍 Hand landmark processing
* ☝️ Index finger tracking
* 🎨 Color selection
* 🖌️ Drawing operations
* 🖥️ Real-time display

---

## 💡 Applications

Air Draw can be used for:

* 👁️ Computer Vision projects
* 🎓 Educational projects
* 🧪 Hand-tracking experiments
* 🖥️ Touchless user interfaces
* 🤖 Human-Computer Interaction experiments
* 🎨 Interactive drawing applications
* 📚 Learning OpenCV and MediaPipe
* 🎤 Interactive presentations and demonstrations

---

## ⭐ Advantages

Air Draw demonstrates how **Computer Vision** can be used to create a simple touchless user interface.

The user does not need:

* 🖱️ A mouse
* ⌨️ A keyboard
* 🖌️ A drawing tablet
* 📱 A touchscreen

A webcam and hand movement are enough to interact with the virtual drawing canvas.

---

## 🚀 Future Improvements

Possible future improvements include:

* 🧹 Add an eraser tool
* 📏 Add brush size control
* 🔷 Add geometric shape tools
* ↩️ Add Undo and Redo functionality
* 💾 Add drawing export and saving
* 🌈 Add more colors
* 🖌️ Add different brush types
* ✋ Support multiple hands
* 🤏 Add gesture-based controls
* 🗑️ Add a gesture for clearing the entire canvas
* ✨ Improve drawing smoothness and quality

---

## 🎯 Project Purpose

The **Air Draw** project was created as a practical **Computer Vision** application to demonstrate how hand tracking can be used to create a touchless and interactive drawing experience.

The project combines:

**📹 Video Processing + ✋ Hand Tracking + ☝️ Finger Tracking + 🎨 Virtual Drawing**

It demonstrates how a simple webcam can be used to create an interactive interface controlled by natural hand movements.

---

## 📄 License

This project is available for personal and educational use.

You are free to study, understand, modify, and improve the project according to your needs.

---

⭐ If you like this project, consider giving the repository a Star.
## 👨‍💻 Developer

**Awab Bashary | AwabBuilds**

GitHub: **awabwdbashry-sketch**
