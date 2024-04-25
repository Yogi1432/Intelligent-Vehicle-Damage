Flask Application for Vehicle Damage Assessment and Cost Estimation

This folder contains the files required to run our flask application forIntelligent vehicle damage assessment and cost estimation with images.
File Structure

.
├── app.py
├── models
│   ├── stage1.h5
│   ├── vehicle_weights.h5
├── static
│   ├── css
│   │   ├── custom.css
│   ├── js
│   │   └── image_upload.js
└── templates
    ├── index.html
    ├── layout.html
    ├── results.html

The folder contains the following Structure:

    app.py: This file contains the flask implementation of the application.
    static folder: This folder contains the following folders:
        css: Contains all CSS files needed to style the application.
        js: Contains the javascript files necessary to run this application (mainly for uploading of image by user).
    templates folder: Contains all HTML files needed by the application.
    models: Contains the models that our team trained, used by our application to detect vehicle damages from an image.

Setup

    Python version used - 3.8.16
    Tensorflow version - 2.12.0
    All training was done on Jupyter Notebooks.
    Dataset used for:
        Damaged/Not damaged: (https://www.kaggle.com/datasets/anujms/car-damage-detection)
        Damage localization: Made by ourselves.
        Damage extremity: Made by ourselves.
    Google Drive link for our Dataset: (https://drive.google.com/drive/folders/1uwSP3DXzjnVyVOxCzGyr8BC00iUiVlCp?usp=sharing)

Running the application

To run the application locally, follow these steps:

    Clone the repository by running the command:
    Change your current working directory to the cloned repository.
    Install all the required libraries for the application.
    Start the application by executing the command:
    python app.py
    Once the application is running, copy the localhost link provided in the terminal output and paste it into your web browser.

By following these steps, you will be able to run the application locally on your machine.
