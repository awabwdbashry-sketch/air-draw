# Air Draw 🎨

Air Draw is a computer-vision drawing application that lets you draw in the air using your index finger. The application uses your webcam to track your hand in real time and turns your finger movements into digital drawings.

## ✨ Features

* Real-time hand tracking
* Draw using your index finger
* Interactive on-screen toolbar
* Multiple drawing colors
* Eraser functionality
* Save your drawing as an image
* Webcam-based interaction
* Smooth and responsive drawing experience

## 🛠️ Technologies

* Python
* OpenCV
* MediaPipe
* NumPy

## ⚙️ How It Works

1. The webcam captures live video.
2. MediaPipe detects and tracks the hand.
3. The application's hand-tracking logic identifies the index finger.
4. Your index-finger movement is converted into drawing strokes.
5. The drawing is displayed on the virtual canvas.
6. You can use the on-screen toolbar to change colors, erase, or save the result.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/air-draw.git
cd air-draw
```

Create and activate a virtual environment:

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

Run the application:

```bash
python air_draw.py
```

Allow the application to access your webcam when prompted.

Use your index finger to draw on the virtual canvas and interact with the on-screen toolbar.

## 🎮 Controls

The application is controlled primarily through hand movements and the on-screen toolbar.

* **Index finger:** Draw
* **Color toolbar:** Change drawing color
* **Eraser:** Remove parts of the drawing
* **Save:** Save the current drawing

> Exact toolbar behavior may depend on the implementation in `air_draw.py`.

## 💻 Requirements

* Python 3.9+
* Working webcam
* Windows, macOS, or Linux
* A device capable of running OpenCV and MediaPipe

## 📚 Dependencies

The project uses:

* `opencv-python`
* `mediapipe`
* `numpy`

All required Python packages are listed in `requirements.txt`.

## 📁 Project Structure

```text
air-draw/
├── air_draw.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚫 Files Not Included

Generated and environment-specific files are intentionally excluded from the repository:

```text
venv/
__pycache__/
*.pyc
drawing.png
```

## 📄 License

This project is available for learning, experimentation, and personal use.
