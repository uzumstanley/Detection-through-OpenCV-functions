# Detection Through OpenCV Functions

**Category:** Computer Vision

![GitHub repo size](https://img.shields.io/github/repo-size/username/Detection-through-OpenCV-functions?color=success)
![GitHub stars](https://img.shields.io/github/stars/username/Detection-through-OpenCV-functions?style=social)
![GitHub forks](https://img.shields.io/github/forks/username/Detection-through-OpenCV-functions?style=social)

A comprehensive demonstration of **color detection**, **shape detection**, **edge detection**, and **image filtering** techniques using [OpenCV](https://opencv.org/) and [matplotlib](https://matplotlib.org/). This project is built to highlight advanced computer vision workflows and Python programming best practices, providing a strong foundation for more complex applications.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Project Structure](#project-structure)  
4. [Requirements](#requirements)  
5. [Installation](#installation)  
6. [Usage](#usage)  
7. [Results](#results)  
8. [Roadmap](#roadmap)  
9. [Contributing](#contributing)  
10. [License](#license)  
11. [Contact](#contact)

---

## Introduction

This repository demonstrates essential **computer vision** tasks often required in real-world scenarios such as robotics, surveillance, and industrial quality control. By leveraging OpenCV functions, the project performs:

- **Color Detection:** Isolating objects based on hue, saturation, and value (HSV color space).  
- **Shape Detection:** Identifying and labeling standard geometrical shapes (triangle, rectangle, pentagon, circle) using contour approximation.  
- **Edge Detection:** Extracting prominent edges and boundaries via the Canny edge detection algorithm.  
- **Image Filtering:** Demonstrating both Gaussian blur (to reduce noise) and custom kernel sharpening (to enhance edges).

This comprehensive project serves as an excellent portfolio piece to exhibit your understanding of classic computer vision algorithms and Python scripting. Recruiters can see your skills in data processing, algorithmic thinking, and effective code documentation.

---

## Features

- **Flexible Color Detection**: Easily modify HSV boundaries to detect different colors in various lighting conditions.  
- **Accurate Shape Classification**: Use polygon approximation to label shapes with minimal false positives.  
- **Robust Edge Detection**: Generate crisp, well-defined edges using the Canny algorithm.  
- **Multi-Stage Image Filters**: Apply Gaussian blur to reduce noise and a custom convolution kernel to sharpen and highlight details.

---

## Project Structure

```
.
├── README.md               # Project documentation
├── main.py                 # Main script that processes the image
├── Results/                # Directory containing the original & processed images
│   ├── original.jpg
│   └── ...
├── Detection-through-OpenCV-functions/  # Repository folder on GitHub
│   ├── ...
│   └── ...
└── requirements.txt        # Dependencies (if you choose to include one)
```

**Note:** Adjust the directory names based on your own layout.

---

## Requirements

- **Python 3.6+**  
- **OpenCV (cv2)**  
- **NumPy**  
- **matplotlib**  

You can include a `requirements.txt` file with these dependencies, for example:

```txt
opencv-python
numpy
matplotlib
```

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/Detection-through-OpenCV-functions.git
   cd Detection-through-OpenCV-functions
   ```
2. **Create and activate a virtual environment** (optional, but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate       # For Linux/Mac
   venv\Scripts\activate          # For Windows
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   Or individually:
   ```bash
   pip install opencv-python numpy matplotlib
   ```

---

## Usage

1. **Place your target images** in the `Results/` folder or specify your own directory.
2. **Run the script** by providing the path to the image:
   ```bash
   python main.py
   ```
3. **Observe** the series of matplotlib windows showcasing:
   - The original image
   - The color-filtered image
   - The shape-labeled image
   - The edge-detected image
   - The blurred image
   - The sharpened image

**Example** usage inside `main.py`:

```python
# Use any image path for testing
image_path = 'Results/original.jpg'
process_image(image_path)
```

---

## Results

Below are snapshots of the results you can expect. These are stored in the `Results/` directory:

1. **Color Detection**  
   ![Color Detection Example](https://github.com/uzumstanley/Detection-through-OpenCV-functions/blob/main/Results/color%20detection%20output.png)

2. **Shape Detection**  
   ![Shape Detection Example](https://github.com/uzumstanley/Detection-through-OpenCV-functions/blob/main/Results/shape%20detection%20output.png)

3. **Edge Detection**  
   ![Edge Detection Example](https://github.com/uzumstanley/Detection-through-OpenCV-functions/blob/main/Results/edge%20detection%20output.png)

4. **Blurred and Sharpened**  
   ![Filtering Example](Results/filtering_exampl)

*Note: Replace these placeholders with your actual screenshots to make your README visually compelling!*

---

## Roadmap

- [ ] **Video Stream Processing**: Extend the script to process live camera feeds or video files in real-time.  
- [ ] **Additional Shape Detection**: Implement more robust shape classification for polygons with more complex criteria.  
- [ ] **Object Tracking**: Add functionality to track detected objects across frames.  
- [ ] **Deep Learning Integration**: Incorporate models like YOLO or Faster-RCNN for more sophisticated object detection tasks.

---

## Contributing

Contributions and suggestions are welcome! To contribute:

1. Fork the repository  
2. Create a new feature branch (`git checkout -b feature/your-feature-name`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature/your-feature-name`)  
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE), which means you are free to modify, distribute, and use the code for your own projects.

---

## Contact

**Author**: Your Name  
- [LinkedIn](https://www.linkedin.com/in/uzum-stanley/)    
- [Email](stanleyuzum@gmail.com)

If you have any questions or would like to collaborate, feel free to get in touch!

---

> **Showcasing this project in your portfolio or resume?** Don’t forget to highlight your mastery of **Python**, **OpenCV**, and **matplotlib**, as well as any innovative features you added to stand out from the crowd!

---  

*Happy coding and best of luck with your computer vision journey!*
