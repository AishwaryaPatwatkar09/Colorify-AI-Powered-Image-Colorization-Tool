# 🎨 ColorifyAI

ColorifyAI is a Streamlit-based application that transforms black and white images into vibrant color using a deep learning model. It also allows you to crop, enhance, apply artistic filters, and compare before-after results — all in a user-friendly interface.

---

## 🧠 Key Features

- ⚙️ **Automatic Image Colorization** using OpenCV’s pretrained DNN models.
- ✂️ **Cropping Tool** powered by `streamlit-cropper`.
- 🎨 **Filters & Blending**: Apply effects like Sepia, Vintage, Pencil Sketch, Cool, Warm, and more.
- 💡 **Auto Enhancement** to improve brightness, contrast, and sharpness.
- 🔄 **Interactive Image Comparison** using a slider.
- 💾 **Download Final Image** after processing.

---
## Project Structure

├── app.py                # Main Streamlit app
├── colorization.py       # Colorizer class using OpenCV DNN
├── filters.py            # Filter application functions
├── image_utils.py        # Utility functions for UI and processing
├── models/               # Folder to store model files
└── colorized_image.png   # Example output
