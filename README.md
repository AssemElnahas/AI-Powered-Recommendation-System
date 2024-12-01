# AI-Powered Movie Recommendation System

This project is a content-based movie recommendation system built using Python and Streamlit. The app suggests movies based on a user’s selection by analyzing the similarities between movie descriptions.

---

## Features
- **Interactive Interface**: Select your favorite movie from a dropdown list.
- **Personalized Recommendations**: Receive recommendations of similar movies.
- **Real-Time Processing**: Instant results with a simple button click.

---

## Technologies Used
- **Python**: Programming language for building the application.
- **Streamlit**: Framework for creating the web app interface.
- **scikit-learn**: Used for calculating text similarity with TF-IDF and cosine similarity.
- **pandas**: Data manipulation and handling.

---

## Installation and Setup
1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. **Install the required dependencies**:
   ```bash
   pip install streamlit pandas scikit-learn
   ```

3. **Run the application**:
   ```bash
   streamlit run app.py
   ```

4. **Access the app**:  
   Open your web browser and navigate to `http://localhost:8501`.

---

## How It Works
1. The app loads a sample dataset of movies with their descriptions and genres.
2. Users select a movie from the dropdown menu.
3. The app calculates the similarity between the selected movie and others using:
   - **TF-IDF Vectorization**: Converts movie descriptions into numerical vectors.
   - **Cosine Similarity**: Finds similar movies based on their descriptions.
4. The app displays the top 3 similar movies as recommendations.

---

## Example Usage
- **User Input**: Select "Inception" from the dropdown.
- **Output**: Recommended movies:
  - Interstellar
  - The Dark Knight
  - Parasite

---

## Customization
- **Add More Movies**: Extend the `load_data()` function with a larger dataset.
- **Enhance Similarity**: Use other NLP techniques like Word2Vec or BERT for advanced similarity calculations.

---

## Contributing
Feel free to contribute to this project by:
1. Forking the repository.
2. Making changes.
3. Submitting a pull request.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments
- Inspired by the capabilities of **Streamlit** for rapid app development.
- Thanks to the **scikit-learn** library for text processing and similarity computation.


