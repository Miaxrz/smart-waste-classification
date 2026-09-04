# Problem Statement

Maintaining a clean and organized workspace is an everyday problem, particularly for students and people who spend long periods working at a desk. A workspace can gradually become cluttered with bottles, cups, food containers, papers, stationery, cables, and other objects.

Currently, determining whether a workspace is sufficiently clean is a manual and subjective process. There is no simple computer-vision-based mechanism that can automatically assess the overall cleanliness of a desk from an image.

This project addresses this problem by developing a lightweight computer vision system that classifies a workspace image into three categories:

1. **Clean** – the workspace contains very little visible clutter and the main working area is clear.
2. **Moderately Cluttered** – several objects are present, but the workspace remains partially usable.
3. **Cluttered** – a significant portion of the workspace is occupied by unnecessary or disorganized objects.

The objective is not to identify every individual object on the desk. Instead, the system focuses on the higher-level decision of whether the workspace requires cleaning or organization.

A custom image dataset will be collected from real workspace environments. Images will be labelled manually according to predefined classification criteria. Multiple machine-learning and deep-learning approaches will then be trained and evaluated under the same data-splitting conditions.

The models will be compared using accuracy, precision, recall, F1-score, confusion matrices, and inference performance.

The final objective is to determine whether a small computer-vision model can provide a reliable first-level assessment of workspace cleanliness while remaining lightweight enough for practical use.

