# 😷 Face Mask Detection

A real-time Face Mask Detection system built using **Python**, **OpenCV**, and **Machine Learning/Deep Learning** techniques to identify whether a person is wearing a face mask or not.

## 📌 Features

* Detects human faces in images or video streams.
* Classifies faces as:

  * ✅ Mask
  * ❌ No Mask
* Supports real-time webcam detection.
* Fast and lightweight implementation using OpenCV.

## 🛠️ Technologies Used

* Python
* OpenCV
* TensorFlow / Keras
* NumPy
* Matplotlib

## 📂 Project Structure

```text
Face_mask/
│
├── dataset/                 # Training dataset
├── model/                   # Saved trained model
├── images/                  # Sample images
├── train.py                 # Model training script
├── detect_mask.py           # Real-time mask detection
├── requirements.txt         # Required dependencies
└── README.md
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/3354-ituku/Face_mask.git
cd Face_mask
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

### Train the model

```bash
python train.py
```

### Run real-time face mask detection

```bash
python detect_mask.py
```

The application will open your webcam and start detecting whether a person is wearing a mask or not.

## 📸 Sample Output

* Green Bounding Box → Face with Mask ✅
* Red Bounding Box → Face without Mask ❌

## 📈 Future Improvements

* Support for multiple faces simultaneously.
* Improve accuracy using larger datasets.
* Deploy as a web application.
* Add support for CCTV camera streams.

## 🤝 Contributing

Contributions are welcome. Feel free to fork this repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**itukunalu**

GitHub: [3354-ituku GitHub Profile](https://github.com/3354-ituku?utm_source=chatgpt.com)
