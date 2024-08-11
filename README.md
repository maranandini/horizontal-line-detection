# horizontal-line-detection
This project is centered on applying machine learning techniques to horizon detection, which is crucial for scenarios where traditional methods like GPS are unavailable. Applications include planetary rover localization, flight control, and port security. The approach starts with Canny edge detection, followed by classifying the detected edges as either "horizon" or "non-horizon" using a Support Vector Machine (SVM) trained on ground truth data and SIFT (Scale-Invariant Feature Transform) features. This method ensures that a consistent horizon line is identified in new images, providing a reliable and adaptable solution for complex real-world challenges.
