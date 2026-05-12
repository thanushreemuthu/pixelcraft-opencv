# Pixel-Level Image Operations Using OpenCV

> OpenCV-based Image Processing and Pixel Manipulation using Python

---

## About the Project

This project demonstrates various pixel-level image processing operations using OpenCV, NumPy, and Matplotlib in Python.

## Aim

To perform image handling and pixel-level transformations using OpenCV in Python by implementing:

- Image reading and displaying
- Brightness manipulation
- Contrast enhancement
- Cropping and resizing
- Image flipping
- RGB and HSV channel operations
- Annotation using text and shapes

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| OpenCV | Image Processing |
| NumPy | Matrix Operations |
| Matplotlib | Image Visualization |
| Jupyter Notebook | Development Environment |

---

## Project Structure

```bash
Pixel-Level-Image-Operations-Using-OpenCV/
│
├── images/
│   ├── Eagle_in_Flight.jpg
│   ├── Apollo-11-launch.jpg
│   └── boy.jpg
│
├── output/
│   ├── grayscale_eagle.png
│   ├── original_color_eagle.png
│   ├── cropped_eagle.png
│   ├── resized_eagle.png
│   ├── flipped_eagle.png
│   ├── apollo_annotated.png
│   ├── brightness_output.png
│   ├── contrast_output.png
│   ├── rgb_channels.png
│   └── hsv_channels.png
│
├── image_processing.py
├── image_processing.ipynb
└── README.md
```
## Algorithm

### Step 1
Read an image using OpenCV.

### Step 2
Display the image dimensions.

### Step 3
Convert grayscale image to color image.

### Step 4
Crop and resize the image.

### Step 5
Flip the image horizontally.

### Step 6
Annotate images using text and rectangle.

### Step 7
Adjust image brightness using matrix addition/subtraction.

### Step 8
Enhance image contrast using scaling factors.

### Step 9
Split and merge RGB channels.

### Step 10
Convert image to HSV and split HSV channels.
## Experimental Outputs

### 1. Grayscale Eagle Image

#### Operation
Reading the eagle image as grayscale.

```text
output/grayscale_eagle.png
```

<p align="center">
<img width="646" height="523" alt="image" src="https://github.com/user-attachments/assets/c9f0d16c-7f0b-4542-8666-5474849e56cf" />
  
</p>

---

### 2. Original Color Eagle Image

#### Operation
Displaying original color image.

```text
output/original_color_eagle.png
```

<p align="center">
<img width="702" height="556" alt="image" src="https://github.com/user-attachments/assets/dd8831e2-0aac-482a-bbad-e1dd92a1173b" />
</p>

---

### 3. Cropped Eagle Image

#### Operation
Cropping only the eagle region.

```text
output/cropped_eagle.png
```

<p align="center">
<img width="523" height="557" alt="image" src="https://github.com/user-attachments/assets/3acf9993-affe-4b2f-b950-9b892b6bbf68" />
</p>

---

### 4. Resized Eagle Image

#### Operation
Resizing image by 2x.

```text
output/resized_eagle.png
```

<p align="center">
<img width="445" height="526" alt="image" src="https://github.com/user-attachments/assets/d82398ac-d2c7-4975-a0d1-21c189ca70ba" />
</p>

---

### 5. Flipped Eagle Image

#### Operation
Horizontally flipping the eagle image.

```text
output/flipped_eagle.png
```

<p align="center">
<img width="672" height="526" alt="image" src="https://github.com/user-attachments/assets/edf8950c-469d-4c45-98fb-3a635b7d2166" />
</p>

---

### 6. Apollo Annotated Image

#### Operation
Adding text and rectangle annotation.

```text
output/apollo_annotated.png
```

<p align="center">
<img width="782" height="478" alt="image" src="https://github.com/user-attachments/assets/ae4e5e40-4aac-482b-920a-33d9b505e5b5" />
</p>

---

### 7. Brightness Adjustment

#### Operation
Creating brighter and darker images.

```text
output/brightness_output.png
```

<p align="center">
<img width="1737" height="444" alt="image" src="https://github.com/user-attachments/assets/1ea530fc-f2e9-429c-9908-268a45c16d0a" />
</p>

---

### 8. Contrast Enhancement

#### Operation
Increasing image contrast using scaling factors.

```text
output/contrast_output.png
```

<p align="center">
<img width="1711" height="428" alt="image" src="https://github.com/user-attachments/assets/aaa008c3-bce3-4011-bba5-af17ed45b240" />
</p>

---

### 9. RGB Channel Splitting

#### Operation
Splitting image into Red, Green, and Blue channels.

```text
output/rgb_channels.png
```

<p align="center">
<img width="1691" height="429" alt="image" src="https://github.com/user-attachments/assets/84d5e8ea-0982-4931-9bae-d06b8128d5ca" />
</p>

---

### 10. HSV Channel Splitting

#### Operation
Splitting image into Hue, Saturation, and Value channels.

```text
output/hsv_channels.png
```

<p align="center">
<img width="1638" height="445" alt="image" src="https://github.com/user-attachments/assets/1ae62c59-e9aa-4ce7-9f2d-d3cfa02440e4" />
</p>

---


