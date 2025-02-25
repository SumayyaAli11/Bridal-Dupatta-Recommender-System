# Bridal Dupatta Recommender System

## Overview
The **Bridal Dupatta Recommender System** is a machine learning-based application designed to recommend bridal dupattas based on image similarity. It leverages precomputed embeddings to find visually similar dupattas, providing users with quick and accurate recommendations.

## Project Structure
```
BridalDupattaRecommender/
├── dataset/                # Folder containing the images of bridal dupattas
├── sample/                 # Sample images for testing and demonstration
├── uploads/                # Directory for user-uploaded images for recommendation
├── README.md               # Project documentation and usage instructions
├── app.py                  # Streamlit web application for user interface
├── embeddings.pkl          # Precomputed image embeddings for similarity search
├── filenames.pkl           # Filenames corresponding to the embeddings
├── main.py                 # Core logic for feature extraction and recommendations
└── test.py                 # Unit tests to ensure code reliability
```

## Requirements
Install the necessary dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
### 1. Running the Web Application
To launch the Streamlit app and interact with the recommender system:
```bash
streamlit run main.py
```
Then, open your browser and navigate to the provided local URL (e.g., `http://localhost:8501`).

### 2. Uploading an Image for Recommendation
- Upload an image of a bridal dupatta.
- The system will display the top visually similar dupattas from the dataset.

### 3. Generating Embeddings (If Needed)
If you update the dataset with new images, generate new embeddings using:
```bash
python app.py
```

### 4. Running Tests
To ensure the code is functioning correctly:
```bash
python test.py
```

## Features
- **Image Upload:** Users can upload an image to get recommendations.
- **Similarity Search:** Utilizes image embeddings to find and display similar dupattas.
- **Streamlit Interface:** User-friendly web interface for seamless interaction.

## Results
- Display of top 5 recommended bridal dupattas with image previews.
- Fast and accurate recommendations based on visual similarity.

## Acknowledgments
- Open-source libraries and contributors.
- Ridah Designs for providing the bridal dupatta images and inspiration.

## Created by
**Sumayya Ali**

