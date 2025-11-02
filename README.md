# 🖋️ Handwriting Digitizer

A Python-based image preprocessing project designed to **digitize handwritten documents** by enhancing image quality for clearer text recognition.  
This project demonstrates how filtering, contrast enhancement, thresholding, and morphological operations can improve the performance of handwriting digitization systems.

---

## 🚀 Features

- 🧹 **Noise Removal** – Cleans background noise using *Gaussian* and *Median* filters.  
- 🌈 **Contrast Stretching** – Enhances visibility through *Histogram Equalization*.  
- ⚫ **Thresholding (Binarization)** – Converts images into clear black-and-white for text isolation.  
- 🧩 **Morphological Operations** – Refines structure using *Opening* and *Closing* operations.  
- 📊 **Result Comparison** – Displays the difference between raw and preprocessed images.

---

## 🧠 Techniques Overview

| Step | Technique | Description |
|------|------------|-------------|
| 1️⃣ | **Noise Removal** | Smooths the image using Gaussian and Median filters to remove unwanted noise. |
| 2️⃣ | **Contrast Stretching** | Expands intensity range to make handwriting more distinct. |
| 3️⃣ | **Thresholding** | Simplifies the image by converting grayscale to binary for better segmentation. |
| 4️⃣ | **Morphological Cleanup** | Fills small gaps and removes small distortions for sharper edges. |

---

## 🧰 Technologies Used

- **Language:** Python  
- **Libraries:** OpenCV, NumPy, Matplotlib  
- **Environment:** Jupyter Notebook (`main.ipynb`)
