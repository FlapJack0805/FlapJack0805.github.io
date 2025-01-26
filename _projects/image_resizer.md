---
layout: page
title: Image Resizer
description: 
img: assets/img/Horse Image.png
importance: 1
category: Software
---


<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/imageresizer.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

For this project, I developed an image resizing tool in C++, utilizing the seam carving algorithm to resize images in a content-aware manner. The tool allows users to shrink images both vertically and horizontally while preserving important features like faces or objects.

Key features of the project include:

-Seam Carving Algorithm: I implemented the seam carving algorithm, which adjusts the size of an image by removing low-energy paths (seams) that have minimal impact on important content. This allows for non-uniform resizing that doesn't distort objects.

-Energy Mapping: The algorithm computes an energy map for the image, identifying areas that can be resized without sacrificing visual integrity. The tool calculates energy values based on gradients to determine the most "unimportant" parts of the image.

-Vertical and Horizontal Resizing: The program supports both vertical and horizontal resizing, giving users the flexibility to adjust the image dimensions while retaining the most significant content.

-Efficient Memory Management: Optimized memory usage was crucial when manipulating large images, and I focused on minimizing overhead and handling dynamic memory allocation effectively.

Through this project, I developed several key skills:

-Algorithm Design: Gained in-depth experience implementing the seam carving algorithm and understanding its application in image processing.

-C++ Programming: Strengthened my proficiency in C++ through dynamic memory management, array manipulation, and optimizing code for performance.

-Image Processing Techniques: Improved my understanding of energy mapping and seam carving, two essential techniques in advanced image resizing.

-Performance Optimization: Focused on improving both time and space efficiency, ensuring the tool could handle large images with minimal lag.
This project reinforced my problem-solving and algorithmic skills while deepening my understanding of computer vision and image processing.



