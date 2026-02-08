🤖 Body Detection 

A simple **Body Detection application** built using **Python and OpenCV** that detects human bodies in images using a Haar Cascade classifier.

📌 Features

* Detects human body in images
* Draws bounding box around detected person
* Uses pre-trained Haar Cascade model

🛠️ Tech Stack

* **Python**
* **OpenCV (cv2)**
* **Haar Cascade Classifier**


📁 Files in this Repository

| File                       | Description                      |
| -------------------------- | -------------------------------- |
| `body.py`                  | Main script for body detection   |
| `haarcascade_fullbody.xml` | Pre-trained body detection model |
| `sample1.jpg`              | Input sample image               |
| `out_sample.jpg`           | Output image with detected body  |
| `Output_frame.PNG`         | Example output frame             |


🚀 How to Run

1️⃣ Install dependencies

```bash
pip install opencv-python

2️⃣ Run the program

```bash
python body.py

📸 Example Output

The detected person will be highlighted with a blue rectangle in the output image (`out_sample.jpg`).

🔮 Future Improvements

* Real-time detection using webcam
* Detect multiple people
* Use deep learning models like YOLO or MediaPipe


👩‍💻 Author

**Pujitha Mamidishetty**

⭐ Feel free to fork, modify, and contribute!
