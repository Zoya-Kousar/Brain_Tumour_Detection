🧠 Brain Tumor Detection Using YOLOv10
This project leverages the YOLOv10 object detection algorithm to accurately identify and localize brain tumors in MRI images. By automating the detection process, it aims to assist medical professionals in early diagnosis and treatment planning.
GitHub

📂 Project Structure
brain-tumor-detection-train.ipynb: Notebook for training the YOLOv10 model on the prepared dataset.

brain_tumor_prediction2.ipynb: Notebook for making predictions on new MRI images using the trained model.

brain_tumor_prediction_for_testing_dataset.ipynb: Notebook for evaluating the model's performance on a separate testing dataset.

data.yaml: Configuration file specifying dataset paths and class names for YOLOv10.

yolov10n.pt: Pre-trained YOLOv10 model weights.

datasets/: Directory containing training and validation images along with their corresponding annotations.

testing images/: Directory containing MRI images used for testing the model's performance.

runs/detect/: Directory where YOLOv10 stores output images with detected tumors during inference.

🧪 Dataset
The dataset comprises MRI images categorized into two classes:
MDPI

Tumor: MRI scans exhibiting the presence of a brain tumor.

No Tumor: MRI scans without any tumor indications.
Biomedical and Pharmacology Journal

Each image is annotated with bounding boxes highlighting the tumor regions, facilitating supervised learning for object detection.
🧪 Methodology
Data Collection: MRI images are collected and organized into training, validation, and testing sets. Each image is annotated with bounding boxes around tumor regions.

Preprocessing: Images are resized and normalized to meet the input requirements of the YOLOv10 model.

Model Training: The YOLOv10 model is trained using the annotated dataset. The training process involves optimizing the model's weights to accurately detect and classify tumors.

Evaluation: The trained model is evaluated on the testing dataset using metrics such as accuracy, precision, and recall to assess its performance.

Inference: The model is used to make predictions on new, unseen MRI images to demonstrate its practical applicability.

📈 Results
The trained YOLOv10 model demonstrates high accuracy in detecting and localizing brain tumors in MRI images. The evaluation metrics indicate the model's effectiveness in distinguishing between tumor and non-tumor cases, providing reliable assistance in medical diagnostics.



