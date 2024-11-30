



Movie Matcher 🎥

Overview
  
Movie Matcher is a movie recommendation system that helps users discover movies they'll love. It uses a blend of machine learning and a user-friendly web interface to provide tailored movie suggestions based on the user’s preferences.

The project consists of two main components:  
- Machine Learning Implementation: A Jupyter Notebook (`preprocessing.ipynb`) where the recommendation system logic is developed.
- Web Application: A sleek and interactive Streamlit app (`app.py`) that brings the recommendation system to life.



Project Features  
- Instant Movie Recommendations: Select a movie and get suggestions for similar titles.  
- Movie Posters: Each recommendation is accompanied by the official movie poster.  
- Intuitive Interface: The app is designed to be simple and user-friendly.    



How It Works  
1. Data Preprocessing  
   - The movie dataset is preprocessed in the Jupyter Notebook using Python libraries like Pandas and NumPy.
   - A similarity matrix is computed using cosine similarity for collaborative filtering.  

2. Web App Functionality  
   - The Streamlit app allows users to select a movie from a dropdown.
   - Based on the user’s choice, the app fetches and displays five similar movies with their posters.

3. Integration with TMDB API  
   - Movie posters are fetched dynamically using the TMDB API.



Setup and Installation  

Prerequisites  
- Python 3.9 or newer  
- Streamlit  
- API Key for TMDB (The Movie Database)

Installation Steps  
1. Clone this repository or download the ZIP file.  
2. Place the required files (movies.pkl, similarity.pkl) in the project directory.  
3. Install the necessary Python libraries:  
   
   pip install streamlit pandas numpy requests
     
4. Run the Streamlit app:  
   
   streamlit run app.py
     
5. Open the app in your browser and start exploring movie recommendations!



 Tools and Technologies Used  
- Programming Language: Python  
- Web Framework: Streamlit  
- Libraries: Pandas, NumPy, Requests, Pickle  
- API: TMDB (The Movie Database) API  



Screenshots (are in the repo)



Future Enhancements  
- Add user profiles to provide personalized recommendations.  
- Allow users to upload watch history for better suggestions.  
- Enhance the recommendation model with hybrid approaches (collaborative + content-based filtering).  
- Improve scalability to handle larger datasets and genres.



Acknowledgements  
This project was developed by Varun S, a passionate Data Science student from Dayananda Sagar College of Engineering. Feel free to reach out for collaborations or suggestions!


