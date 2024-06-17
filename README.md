# Textile-Image-Processing

PunchCardVision is a Python project that utilizes computer vision techniques to analyze and interpret punched card images. It can process punched card images, identify the presence or absence of punches in each column, and generate visual representations of the punched card data.

## Features

- **Image Preprocessing:** The project includes functions to preprocess punched card images, such as resizing and applying binary thresholding.
  
- **Segmentation:** It divides the preprocessed image into vertical segments corresponding to individual columns and then divides each column into horizontal segments representing punch positions.

- **Contour Detection:** Using contour detection techniques, the project identifies the presence of punches within each segment.

- **Visualization:** Punch presence is visualized using color-coded representations, making it easy to interpret the data at a glance.


## Output
Here is a example of visualized punched card data:

**Colored Representation**

![Colored_Image](https://github.com/Madhu-2101/PunchCardVision/assets/86066580/9b737fa8-4c2f-44de-9df1-7a4b22a38da0)

