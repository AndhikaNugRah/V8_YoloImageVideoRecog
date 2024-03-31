# YOLO Object Detection App (Image & Video Support) with Confidence Threshold Control

# Introduction:

This Streamlit application empowers you with real-time object detection capabilities using the powerful YOLOv8 model. It utilizes a pre-trained model, stored conveniently in action_file.py and format in format_file.py, for efficient image and video processing.

# Key Features:

1.Image & Video Object Detection: Upload images (JPG, PNG, JPEG) or videos (MP4) and get real-time detections with YOLOv8.
2.Pre-trained YOLOv8 Model: A pre-trained YOLOv8 model resides in format_file.py for streamlined deployment. (Consider mentioning the model name or source if applicable)
3.Streamlit Integration: The intuitive Streamlit framework facilitates a user-friendly interface for file selection and visualization.
4.Configurable Confidence Threshold: Refine results by adjusting the confidence threshold (25-100%) to filter out low-certainty detections.

# Getting Started

1. Prerequisites:

Python 3.x (https://www.python.org/downloads/)
pip package manager (comes bundled with Python)

2. Installation:

Clone or download the repository containing your application files: self_model_DhikaN.py, format_file.py (likely contains helper functions), and action_file.py (optional, stores configuration settings). Open a terminal or command prompt and navigate to the downloaded directory using the cd command:

3. Run the Application:

In the same terminal window, execute the following command to start the Streamlit app using self_model_DhikaN.py:

streamlit run self_model_DhikaN.py

4. Usage:

A web browser window will automatically open, displaying the user interface of your Streamlit application. The interface might offer options for:

Source Selection: Choose between "Image" or "Video" using radio buttons.
File Upload: Select an image or video to process.
Confidence Threshold (Optional): Adjust the slider to filter detections based on confidence level (25-100%).
Detection Results: View the processed image or video frame with bounding boxes drawn around detected objects. Additional details may be accessible through expanders.

Explanation:
The application loads the pre-trained YOLOv8 model stored in action_file.py. Depending on your selection (image or video), it processes the uploaded file and applies object detection using the model. The confidence threshold allows you to control the minimum certainty level for displayed detections.

# Troubleshooting:
If you encounter errors, double-check:
All necessary files are downloaded in the same directory.
Dependencies are installed correctly using pip.
Paths specified in self_model_DhikaN.py for loading the model and settings (if applicable) are accurate.
Pre-trained model compatibility with YOLOv8 and format (e.g., PyTorch weights).

#Additional Notes:
You can customize the user interface by modifying the Streamlit code in self_model_DhikaN.py for a tailored experience.
Explore advanced features in YOLOv8 and Streamlit, such as different object detection algorithms and real-time webcam video processing (if supported by your code).
Refer to the documentation of format_file.py and action_file.py (if present) for specific instructions on configuring the application.
