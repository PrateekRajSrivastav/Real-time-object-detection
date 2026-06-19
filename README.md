**Real-Time Object Detection using YOLOv8**
Built a real-time object detection pipeline using **Python, YOLOv8, OpenCV, Ultralytics, and Roboflow** to accurately detect and classify objects in images and video streams. I created the complete computer vision workflow, including dataset annotation, preprocessing, model training, evaluation, and inference, while optimizing the model for real-time performance. During development, I learned how dataset quality, annotation accuracy, and hyperparameter tuning significantly impact detection accuracy and model performance.

The biggest learning was that model performance depended more on the quality of the training dataset and annotations than on simply training for more epochs. Small improvements in data preprocessing and labeling consistency produced better results than increasing model complexity, reinforcing the importance of data quality in AI systems.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Dataset & Annotation:
The dataset was created and managed using Roboflow, where images were annotated, preprocessed, augmented, and exported in YOLOv8 format for model training.
roboflow link: https://app.roboflow.com/prateek-raj-srivastav/object-tracking-sem8/models/object-tracking-sem8/1

Training Notebook:
The complete implementation is available in Google Colab, including dataset loading, YOLOv8 model training, evaluation, inference, and visualization using the Ultralytics framework and OpenCV.
colab link: https://colab.research.google.com/drive/1AkshJ4FtKz1xLtlnONSnOvJ9m4dWi3Vn?usp=sharing
