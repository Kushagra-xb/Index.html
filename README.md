# Sign to Text

A beginner-friendly web prototype that uses a live camera feed and MediaPipe Hand Landmarker to detect and display hand landmarks.

> **Current scope:** This project detects hand landmarks in real time. It does not recognize signs or translate sign language into English yet.

## Screenshot

![Sign to Text showing detected hand landmarks](Project/screenshot.png)

To add the screenshot, run the project, show your hand so the landmark dots are visible, take a screenshot, and save it as `Project/screenshot.png`.

## Run locally

1. Clone this repository.
2. Open the repository folder in Visual Studio Code.
3. Open `Project/projectX.html` with the Live Server extension.
4. Allow camera access when your browser asks.
5. Wait for the hand tracker to load, click **Start Camera**, and hold a hand in view.

Open the page through `localhost` or HTTPS. Camera access usually won’t work if you open the HTML file directly as a `file://` URL. An internet connection is needed to load MediaPipe and its WebAssembly files.

## Project structure

```text
Project/
├── models/
│   └── hand_landmarker.task
└── projectX.html
README.md
