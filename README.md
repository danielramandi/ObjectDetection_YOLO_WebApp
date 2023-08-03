# Object Detection with YOLO (WebApp)

This repository contains a Streamlit-based web application for performing object detection using the YOLO (You Only Look Once) algorithm.

Folder Structure:

    'codes/': Contains the main script ('main.py') and the configuration files.
    'codes/config_n_weights/': Contains the configuration file for YOLO ('yolov3.cfg').
    'Gallery/': Contains example images and videos that can be used for testing.

Getting Started:

Follow these steps to get started with this project:

    Clone the repository:
    git clone https://github.com/danielramandi/ObjectDetection_YOLO_WebApp.git

    Navigate into the project directory:
    cd ObjectDetection_YOLO_WebApp

    Download the YOLOv3 weights file into the 'codes/config_n_weights/' directory. You can do this with the following command:
    wget https://media.githubusercontent.com/media/patrick013/Object-Detection---Yolov3/master/model/yolov3.weights -P codes/config_n_weights/

    Run the Streamlit app using the command:
    streamlit run codes/main.py

You should now be able to access the web application on your local machine.

How to Use:

Once you've got the web application running:

    Select an image or video from the 'Gallery/' folder.
    Click "Upload" to upload the selected file.
    Click "Run" to perform object detection on the uploaded file. The results will be displayed on the page.

Dependencies:

This project relies on Streamlit for the web interface. Ensure you have it installed by running:
pip install streamlit
