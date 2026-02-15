AI-HAIR: Hairstyle Recommendation System
🔍 Overview

This project is an AI-powered application designed to recommend the most suitable hairstyles for users based on their unique facial features. By analyzing a user's face shape and hair texture, the system suggests styles that complement their natural appearance.
🚀 Key Features

    Face Shape Detection: Uses computer vision (OpenCV/MediaPipe) to identify face shapes such as Oval, Round, Square, Heart, and Oblong.

    Feature Extraction: Measures facial landmarks including jaw width, face height, and eyebrow arch to ensure precision.

    Hair Texture Analysis: Utilizes a Convolutional Neural Network (CNN) to classify hair as curly, straight, or wavy.

    Personalized Suggestions: Matches user data against a curated dataset of celebrity images and professional styles to provide tailored recommendations.

    Interactive UI: A simple interface for uploading photos or using a webcam for real-time analysis.

🛠️ Tech Stack

    Languages: Python, Jupyter Notebook

    Libraries: OpenCV, MediaPipe, TensorFlow/Keras (for CNN), Scikit-learn

    Backend/Framework: Flask (if deployed as a web app)

📂 Project Structure

    data/: Contains datasets for face shapes and hair textures.

    models/: Pre-trained weights for VGG16 and custom CNN models.

    scripts/: Python scripts for image pre-processing (scaling, rotating, cropping).

    notebooks/: Exploratory Data Analysis and model training steps.

⚙️ How to Run

    Clone the repository:
    Bash

    git clone https://github.com/2007aman/AI-HAIR.git

    Install dependencies:
    Bash

    pip install -r requirements.txt

    Run the application:
    Bash

    python app.py

🔮 Future Roadmap

    Integration of Augmented Reality (AR) for virtual "try-on" experiences.

    Gender-specific filtering for more accurate styling.

    Cloud deployment for mobile access.
