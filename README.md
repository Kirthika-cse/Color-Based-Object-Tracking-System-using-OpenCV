
🎯Color-Based Object Tracking System using OpenCV


 📖 Overview
This project implements a **real-time color-based object tracking system** using **OpenCV** and **Python**.  
It detects and tracks colored objects using the **HSV (Hue, Saturation, Value)** color space, allowing users to dynamically adjust detection parameters through a **Tkinter-based GUI**.  

---

 🧠 Key Features
- 🎨 **Color-based tracking** using HSV color scaling.
- 🧰 **Interactive GUI** built with Tkinter for real-time parameter tuning.
- 🧮 **Data processing** with NumPy, Scikit-Image, SciPy, and Pillow.
- 📷 **Real-time camera input** via OpenCV.
- ⚙️ **Automation support** with PyAutoGUI for region capture and scaling.
- 🔍 Adjustable **Hue, Saturation, and Value sliders** for accurate color detection.

---

🧑‍💻 Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - OpenCV  
  - Pillow (PIL)  
  - NumPy  
  - SciPy  
  - Scikit-Image  
  - PyAutoGUI  
  - Tkinter  

---

⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Color-Based-Object-Tracking-System-using-OpenCV.git
   cd Color-Based-Object-Tracking-System-using-OpenCV
````

2. Install required dependencies:

   ```bash
   pip install opencv-python
   pip install opencv-contrib-python
   pip install  pandas numpy imutils pillow scipy scikit-image pyautogui
   ```

3. Run the application:

   ```bash
   python colorCalibrationforHSV.py  (for choosing the HSV values of the object)
   python main.py
   ```

---

 🖥️ How It Works

1. The system captures video frames through the webcam.
2. Converts the image from BGR to HSV color space.
3. Creates a color mask based on the user’s hue, saturation, and value slider settings.
4. Detects and tracks the selected color in real time.
5. Displays live feedback with object position and movement direction.

---

 📊 Example Output

* Tracks colored objects in real time.
* Displays object’s contour, center, and movement direction (e.g., Left, Right, Front, Stop).

---

🧩 Future Enhancements

* Add multi-color tracking support.
* Integrate object size estimation.
* Save tracking data for analysis.
* Include object detection via deep learning models (YOLO, SSD).

---

🏆 Author

Kirthika R S
Bachelor of Engineering (Honours) – Computer Science
[East West Institute of Technology (VTU), Bangalore]

---

📎 License

This project is licensed under the **MIT License** — feel free to use and modify it.

```
