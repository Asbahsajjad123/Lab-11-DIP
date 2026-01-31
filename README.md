# Lab-11-DIP
1.	Perform erosion, dilation, opening, closing.
2.	Extract boundaries.
3.	Fill holes using reconstruction.
4.	Remove noise using morphology.
5.	Detect specific shapes.
# Cpde Explanation
This code demonstrates morphological image processing operations using OpenCV in Google Colab. First, a grayscale image is uploaded and converted into a binary image using thresholding. A 5×5 structuring element is defined and used to perform basic morphological operations such as erosion and dilation, which shrink and expand foreground objects respectively. Opening and closing operations are then applied to remove small noise and fill small gaps in objects. Boundary extraction is performed by subtracting the eroded image from the original binary image to highlight object outlines. Hole filling is achieved using morphological reconstruction by dilation, where internal holes in objects are filled while preserving their shape. Noise removal is again demonstrated using morphological opening. Finally, shape detection is carried out by finding contours and approximating their polygonal shapes to classify objects as triangles, rectangles, circles, or unknown shapes. All intermediate and final results are displayed together to visually compare the effects of each morphological operation.
