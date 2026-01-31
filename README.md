# Anime-Success-Predictor
A deep learning model to predict the MyAnimeList user score for any given anime metadata.
📺 Anime Success Predictor
A Deep Learning approach to predicting MyAnimeList scores.

📌 Project Overview
Can we predict how much the anime community will love a show before it even airs? This project uses a Deep Neural Network to analyze the relationship between an anime's metadata (Studio, Genre, Theme, Source Material) and its final user rating on MyAnimeList.

By processing over 14,000 titles, this model identifies the complex patterns that lead to a "masterpiece" rating versus a "flop."

🚀 Key Features
Deep Learning Architecture: A 4-layer Sequential Neural Network built with TensorFlow/Keras.

High-Dimensional Data: Utilized One-Hot Encoding to transform categorical metadata into a 995-feature vector.

Advanced Data Cleaning: Implemented custom imputation logic to handle missing themes and studio data, preserving 40% more data than standard row-deletion.

Interactive Demo: Includes a Python-based interface for real-time "What-If" analysis of hypothetical anime.

📊 Results
The model's performance was evaluated using Mean Absolute Error (MAE).

Final Test MAE: 0.4826

Interpretation: On average, the model's predictions are accurate within ~0.48 points of the actual MAL score (on a 1-10 scale).

🛠️ Tech Stack
Language: Python

Libraries: TensorFlow, Keras, Pandas, NumPy, Scikit-Learn, Matplotlib

Environment: Google Colab / Jupyter Notebooks

📂 Dataset
The data consists of 14k+ entries with features including:

Type: (TV, Movie, OVA, etc.)

Source: (Manga, Light Novel, Original, etc.)

Metadata: Genres, Themes, Studios, and Episode counts.
