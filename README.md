# ProjectADPRO-1

# Edge Detection and Image Cropping Tool

## Description
This tool allows you to crop and perform edge detection on images using various algorithms. It supports multiple edge detection algorithms, including Canny, Sobel, Laplacian, Prewitt, Roberts Cross, and Gaussian. Additionally, the tool can batch process multiple images simultaneously, making it easy to work with large sets of images.

## Key Features
- **Edge Detection** using various algorithms
- **Image Cropping** with customizable selection areas
- **Batch Processing** for edge detection and cropping

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Endless1612/ProjectADPRO-1.git

## Usage

### 1. Upload Image
- Click the **Upload Image** button or **Drag and drop** your images onto the application. You can upload individual images (PNG, JPG) or ZIP files containing multiple images.
- The uploaded images will appear in the image container at the bottom.

### 2. Select and Crop
- After uploading, select an image and click **Start Crop**. You can now draw a rectangular selection on the image.
- Adjust the cropping area as needed, then click **Confirm Crop** to finalize.
- To crop multiple images at once, use **Batch Crop** for batch cropping mode.

### 3. Edge Detection
- Choose an edge detection algorithm from the **Select Method** dropdown. Supported algorithms include Canny, Sobel, Laplacian, Prewitt, Roberts Cross, and Gaussian.
- Adjust the specific parameters for the selected algorithm (e.g., thresholds, kernel size) using the sliders and options displayed.
- Click **Detect Edges** to apply the edge detection algorithm to the selected image(s).

### 4. Batch Processing
- To process multiple images at once, use the **Select** or **Select All** buttons to pick your images, then click **Confirm Select**.
- Click **Batch Crop** to crop all selected images simultaneously, or **Detect Edges** to run edge detection on all selected images.

### 5. Save Processed Images
- After cropping or edge detection, click **Save Image** to save the current image.
- For batch saving, click **Save All Result** to save all processed images as a ZIP file.

### 6. Revert to Original
- If you want to undo any edits, click **Revert to Original** to reset the image back to its original state.

### 7. Zoom In and Out
- Use the **+** and **-** buttons to zoom in or out on the image. Click **Reset Zoom** to return to the default zoom level.

### 8. Clear Images and Results
- Use the **File** menu options to clear selected images, stored images, or result images as needed.
- **Clear selected** will remove images from the current selection.
- **Clear image** will remove all images from the current session.
- **Clear result image** will remove all processed images from the results area.