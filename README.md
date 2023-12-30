# extractTilesPyvips
Tiles extraction from Whole slide Images using Pyvips and save it in labels-specific directories
This notebook focuses on a tile generation process essential for handling large-scale image datasets, frequently encountered in fields such as medical imaging. The primary goal is to efficiently preprocess high-resolution Whole Slide Images (WSI) into smaller, manageable tiles for downstream analysis and machine learning tasks.

Advantages Over Other Approaches:

-Handling Large Image Dimensions (Overcoming Size Limitations):

This approach addresses the challenge posed by image sizes beyond the constraints of traditional image processing libraries like OpenCV (cv2), which typically have limitations on image dimensions (e.g., 32,000x32,000 pixels). Unlike cv2, Pyvips facilitates the handling of WSIs that exceed such dimensions.

-Supporting WSIs in PNG Format:

Many datasets in medical imaging and pathology comprise Whole Slide Images in formats like PNG, which aren't directly supported by libraries such as OpenSlide. While OpenSlide can manage huge images, it does not support WSIs in PNG format. Pyvips enables PNG image processing tasks.
