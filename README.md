# MorphologicalCompression-Image-ProcessinG
📖 Overview

This repository contains Lab 11: Morphological Operations, implemented using Python and OpenCV.
The lab demonstrates how morphological image processing techniques are used for shape analysis, noise removal, boundary extraction, hole filling, and object detection in binary images.

🎯 Objectives

The objectives of this lab are to:

Apply basic morphological operations such as erosion, dilation, opening, and closing

Extract object boundaries using morphology

Perform hole filling using morphological reconstruction

Remove noise from binary images

Detect and label specific shapes using contour analysis

🛠 Technologies Used

Python 3.x

OpenCV (cv2)

NumPy

🖼 Image Requirements

This lab requires one binary image with the following characteristics:

Black background

White foreground objects

Clearly visible shapes (blobs / circles / objects)

Small holes inside objects

Salt-and-pepper noise

📌 A single image is sufficient to perform all tasks in this lab.

📂 Project Structure
Lab11_Morphological_Operations/
│
├── input/
│   └── MORPHOLOGICAL IMAGE.png
│
├── output/
│   ├── erosion.png
│   ├── dilation.png
│   ├── opening.png
│   ├── closing.png
│   ├── boundaries.png
│   ├── holes_filled.png
│   ├── noise_removed.png
│   └── shape_detection.png
│
└── lab11_morphology.py

🧪 Tasks Implemented
✅ Task 1: Morphological Operations

Erosion

Dilation

Opening

Closing

✅ Task 2: Boundary Extraction

Object boundaries extracted using erosion difference

✅ Task 3: Hole Filling

Holes inside objects filled using morphological reconstruction

✅ Task 4: Noise Removal

Noise removed using opening operation

✅ Task 5: Shape Detection

Contour detection

Shape classification (circle / blob based detection)

Shapes labeled on output image

📤 Output Files

The following output images are generated and saved automatically:

erosion.png

dilation.png

opening.png

closing.png

boundaries.png

holes_filled.png

noise_removed.png

shape_detection.png

▶ How to Run

Clone the repository:

git clone https://github.com/your-username/Lab11-Morphological-Operations.git


Place your input image in the input folder:

input/shapes.png


Run the Python script:

python lab11_morphology.py


View results in the output folder.

🧠 Conclusion

Morphological operations play a vital role in image processing by enabling effective object analysis, noise suppression, and shape detection.
This lab demonstrates how a single binary image can be used to perform multiple morphological tasks efficiently.

👩‍💻 Author

Bushra
Software Engineering Student
