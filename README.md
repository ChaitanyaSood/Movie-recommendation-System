# Movie-recommendation-System

This project utilizes pandas, Scikit-learn, numpy, pickle, streamlit(creating simple and elegant web applications in pure Python) to create a basic project on movie recommendation system. The system is designed to take an input of movies from the user and recommend five similar movies from the tmdb-5000-movies available on [Kaggle](https://www.kaggle.com/datasets/chaitanyasood1/tmdb-5000-movies).

## Features

- Recommends five movies similar to the input movie from the tmdb_5000_movies Dataset.
- Utilizes Scikit-learn for calculating nearest neighbors for recommendation.

## Target Audience

This project is beneficial for developers and machine learning enthusiasts looking to understand and implement movie recommendation systems.

## Technical Details

- Python 3.9.0 is used for development.
- TensorFlow 2.10, Scikit-learn 1.3.0, Numpy, Pickle, tqdm and the ResNet-50 model from TensorFlow are the primary dependencies.
- Two pickle files trained on the Fashion Product Images Dataset are required for the system to recommend similar images.
- CUDA installation might be required so that Tensorflow can use the dedicated GPU (CUDA can speed up the process of pickle file generation)
  
## Installation and Usage

1. Download the complete folder from the drive link provided below.

2. Open the .ipynb file and change the path to the datasets.
   
3. Run the .ipynb file and install the required libraries.
   
4. Run the app.py file. 

5. In the terminal type:

    streamlit run app.py

   ![image](https://github.com/ChaitanyaSood/Movie-recommendation-System/assets/96310627/3ac00b30-17f6-446e-bf80-43287bacf46b)


   a webpage will open in your browser where you can enter the movie existing in the dataset. click on recommend for getting recommendations.

   ![image](https://github.com/ChaitanyaSood/Movie-recommendation-System/assets/96310627/76df363d-e4e2-4e9e-9157-c136e2850eaa)


## Additional Information

### Links and Resources

1. [Fashion Product Images Dataset on Kaggle](https://www.kaggle.com/datasets/chaitanyasood1/tmdb-5000-movies)

2. Link to the Google Drive for required pickle files: [Google Drive](https://drive.google.com/drive/u/0/folders/1RkR0O5QndDT-kUH8WSZdCu9E-AzKxhGy)
   You might need to generate Filenames.pkl file again to make the project work
   
### Future Plans

Future updates may include:

- Optimization of recommendation algorithms.
- Support for more movies in the datasets.
- Integration with mobile applications for user-friendly interactions and hosting the web application.
