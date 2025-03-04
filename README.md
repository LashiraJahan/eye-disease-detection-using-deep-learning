# eye-disease-detection-using-deep-learning
Eye Disease Detection is an end-to-end solution using transfer learning and Flask for classifying eye diseases from images. The project trains a VGG19 model on augmented eye image datasets and provides a responsive web interface for image upload and prediction. It detects cataract, diabetic retinopathy, glaucoma, and normal eyes effectively.
dataset/
├── Cataract/
│   ├── image1.jpg
│   └── ...
├── Diabetic_Retinopathy/
│   ├── image1.jpg
│   └── ...
├── Glaucoma/
│   ├── image1.jpg
│   └── ...
└── Normal/
    ├── image1.jpg
    └── ...
Eye_Disease_Detection/
├── app.py                   # Flask web application
├── model_training.py        # Script to train and save the model
├── requirements.txt         # Python dependencies
├── README.md                # Project overview and instructions
├── dataset/                 # Raw dataset (organized in subfolders by class)
├── output/                  # Folder created by splitfolders (training/validation split)
├── uploads/                 # Folder for uploaded images (created at runtime)
├── templates/               # HTML templates for the Flask app
│     └── index.html
└── static/
      └── index.css        # Custom CSS styles
