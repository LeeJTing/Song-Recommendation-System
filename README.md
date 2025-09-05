# Song-Recommendation-System
AI assignment

Before running the application, please install the libraries below:
# Core data processing and machine learning libraries
pip install numpy
pip install pandas
pip install scikit-learn
pip install scipy

# Visualisation libraries (for data analysis)
pip install matplotlib
pip install seaborn

# Sentence transformers for semantic similarity
pip install sentence-transformers

# PyQt5 for GUI
pip install pyqt5

# Additional Qt multimedia components (for audio playback)
pip install pyqt5-tools

# How to Run our Application
Select the Hybrid_Recommendation_System.ipynb file and run it.

After running the app, users will be directed to the homepage. The homepage offers three search options: searching by song title or keyword, logging in, or clicking "Advanced" to search for songs matching specific characteristics. First, searching for a song in the search bar will display a list of six recommended songs below. Users can select a song from the list or press Enter to search. Second, clicking "Advanced" will lead to the Advanced Search page, where users can select song details, including genre, label, year, time, and danceability, and then click "Apply Filters" to find songs that match their preferences. Third, logging in with their ID will result in a list of five recommended songs in the "Recommended for You" section of the homepage based on their listening history. Finally, if users are logged in and search using keywords or song titles, the system will recommend 11 songs based on the search result and their previous listening history.