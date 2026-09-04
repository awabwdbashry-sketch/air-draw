# Air Draw

Air Draw is a real-time virtual drawing application that allows you to draw in the air using your hand and webcam.

The project uses **OpenCV** for real-time video processing, **MediaPipe** for hand tracking, and **NumPy** for image and drawing operations.

Instead of using a physical mouse, keyboard, or drawing tablet, the user can control the drawing canvas using their **index finger**.

---

## Features

* Real-time hand tracking using a webcam
* Draw in the air using the index finger
* Virtual drawing canvas
* Color selection toolbar
* Multiple drawing colors
* Smooth real-time drawing
* Hand landmark detection
* Automatic detection of the index finger
* Live camera preview
* Simple and interactive interface
* No physical drawing device required

---

## Technologies Used

* **Python**
* **OpenCV**
* **MediaPipe**
* **NumPy**

---

## How It Works

The application uses the webcam to capture live video frames.

MediaPipe detects the user's hand and identifies its landmarks. The application then tracks the position of the **index finger**.

When the index finger moves across the screen, its position is used as a virtual drawing point.

The application continuously connects the detected finger positions to create a drawing on the virtual canvas.

A color toolbar is also available, allowing the user to select different drawing colors.

### Processing Pipeline

```text
Webcam
   ↓
Video Frame
   ↓
MediaPipe Hand Detection
   ↓
Hand Landmarks
   ↓
Index Finger Detection
   ↓
Finger Position Tracking
   ↓
Drawing on Canvas
   ↓
Display Result
```

---

## Drawing Controls

The main interaction is based on the index finger.

* **Index finger** → Used as the drawing tool
* **Finger movement** → Creates the drawing
* **Color toolbar** → Changes the drawing color
* **Webcam** → Provides the real-time input

The exact interaction behavior depends on the current implementation of `air_draw.py`.

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/awabwdbashry-sketch/air-draw.git
```

### 2. Open the project directory

```bash
cd air-draw
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Requirements

The project requires:

```text
opencv-python
mediapipe
numpy
```

A working webcam is also required.

---

## Usage

After installing the dependencies, run:

```bash
python air_draw.py
```

The application will start the webcam and begin detecting the user's hand.

Move your index finger in front of the camera to draw on the virtual canvas.

Use the color toolbar to select the desired drawing color.

---

## Project Structure

```text
air-draw/
│
├── air_draw.py
├── README.md
├── README_AR.md
├── requirements.txt
└── .gitignore
```

### Main File

**`air_draw.py`**

Contains the complete implementation of the virtual air drawing application, including:

* Webcam capture
* Hand detection
* Hand landmark processing
* Index finger tracking
* Drawing operations
* Color selection
* Real-time display

---

## Applications

Air Draw can be used for:

* Computer vision demonstrations
* Hand gesture interaction experiments
* Educational projects
* Interactive presentations
* Human-computer interaction experiments
* Touchless interfaces
* Creative drawing applications
* Learning MediaPipe and OpenCV

---

## Advantages

Air Draw demonstrates how computer vision can be used to create a simple touchless user interface.

The user does not need:

* A mouse
* A keyboard
* A drawing tablet
* A touchscreen

A webcam and hand movements are enough to interact with the drawing canvas.

---

## Future Improvements

Possible improvements include:

* Adding more drawing tools
* Adding an eraser
* Adding brush size control
* Adding shape tools
* Adding undo and redo
* Saving drawings in different formats
* Adding more colors
* Improving drawing smoothness
* Supporting multiple hands
* Adding gesture-based controls
* Adding a clear-canvas gesture

---

## Project Purpose

This project was created as a practical computer vision project to demonstrate real-time hand tracking and touchless interaction using Python.

It combines webcam processing, hand landmark detection, finger tracking, and virtual drawing into a simple interactive application.

---

## License

This project is available for educational and personal use.

You are free to study, modify, and improve the project according to your needs.
