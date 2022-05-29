# Cinemate
# Cinemate





Cinemate is a Content- based movie recommendation webapp built using Cosine similarity which provides movie recommendations similar to the user's preferences .
 
## Content based Filtering and Cosine Similarity
Content Based Filtering- They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.



Cosine similarity- It is a metric used to determine how similar documents are regardless of their size. It estimates the cosine of the angle formed by two vectors projected in a multi-dimensional space mathematically. Because of the cosine similarity, even if two comparable documents are separated by the Euclidean distance (due to the size of the documents), they are likely to be orientated closer together. The larger the cosine similarity, the smaller the angle.
## How to run the project ?
1. This repository may be cloned or downloaded to your own PC.
Using the command pip install -r requirements.txt, install all the libraries listed in the requirements.txt file.

2. Go to https://www.themoviedb.org/ to get your API key.

3. Replace YOUR API KEY in both locations in the static/recommend.js file (lines 15 and 30) and save.
4. Using the command python main.py, open your terminal/command prompt and run the file main.py from your project directory.
5. In the address box of your browser, type http://127.0.0.1:5000/.
6. And its DONE!


## How to generate API key ?

Create an account at https://www.themoviedb.org/, then go to your account settings and click on the API link in the left hand sidebar to generate an API key. If a website URL is requested, simply state "NA" if you do not have one. Once your request is granted, the API key will appear on your API sidebar.
