# Disaster-Management-And-Prediction-System
# Overview
This project aims to develop advanced image classification for earthquakes, wildfires, and floods, aiding emergency response with timely insights. Additionally, we're creating a sophisticated people detection algorithm to assess human impact, prioritize rescue efforts, and integrate both modules into user-friendly software for real-time disaster management support.

![Disaster-Management-And-Prediction-System](https://github.com/Liorohan10/Disaster-Management-And-Prediction-System/blob/master/Untitled%20video%20-%20Made%20with%20Clipchamp.mp4)

# Features
* Image Classification 
  * Classify input images into one of three categories, earthquake, wildfire or flood. 
  * Proved relevant evaluation metrics for each category.
* Person Detection
  * Used YOLOv8 to detect people within the input image.
  * Provided bounding boxes around detected people.
  * Estimated number of people detected.
* Scalability
  *  Created a scalable system which can handle numerous requests at the same time. 
* User Interface
  * Developed a user interface (UI) for users to upload images and view classification results and person detections through a website.

* Technical Requirements
  * Programming language: Python, JavaScript, HTML, CSS
  * Deep Learning Framework: TensorFlow, PyTorch
  * Model:
     * Leveraged a pre-trained Vision Transformer from Hugging Face (google/vit-base-patch16-224) fine tuned on a custom dataset.
     * Utilised a pre-trained YOLOv8-nano model for person detection which was fine-tuned on a custom dataset.
        
