# Movie Recommendation System

## Introduction
This project focuses on designing a content-based movie recommendation system that suggests five similar movies based on user input. The system utilizes text vectorization techniques, specifically Bag of Words, and the TMDB 5000 Movie Dataset from Kaggle to train the recommendation model.

## Features
- Recommends five similar movies based on user input.
- Utilizes Bag of Words text vectorization techniques to convert movie descriptions into numerical representations.
- The recommendation system is designed to be content-based, meaning it suggests movies based on their similarity to the user's preferred movie.
- The TMDB 5000 Movie Dataset from Kaggle is used for training and evaluation purposes.
- Technologies used: Supervised Learning, Sklearn, Pandas, NumPy, Python.

## Installation
1. Clone this repository: `git clone <repository_url>`
2. Install the required dependencies by running: `pip install -r requirements.txt`
3. Download the TMDB 5000 Movie Dataset from Kaggle and place it in the designated data folder.
4. Run the main application script: `python movie_recommendation.py`

## Usage
1. Ensure that the dataset is properly loaded and preprocessed by running the data preprocessing script: `python data_preprocessing.py`.
2. Train the recommendation system model by executing the training script: `python train_model.py`.
3. Once the model is trained, the main application script can be used to receive user input and recommend five similar movies: `python movie_recommendation.py`.

## Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
1. Fork this repository.
2. Create a new branch: `git checkout -b my-new-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request detailing your changes.

## License
This project is licensed under the [MIT License](LICENSE).
