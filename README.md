# Movie Recommendation Web App

This is a lightweight, interactive web application that recommends movies based on the user's preferred genres. I developed this alongside my university team as a practical project to explore Python web frameworks and simple data parsing.

## How it works
Instead of setting up a complex backend and a SQL database, we kept things fast and efficient:
* **The Interface:** Built entirely in Python using **Streamlit**. It creates a clean, responsive UI where users can input their name and pick multiple genres from a dropdown list.
* **The Data:** All movie metadata (titles, genres) is stored in a simple, easy-to-read `movies.json` file. 
* **The Logic:** When the user hits the "Sugerează filme" button, a custom Python function reads the JSON data and uses set intersections (via Python's `any()` function) to instantly filter and display matching movies.

## Tech Stack
* **Python 3**
* **Streamlit** (for the web frontend)
* **JSON** (for lightweight data storage)

## 🚀 How to run it locally
If you want to test the app on your own machine, follow these steps:

1. Clone this repository or download the files.
2. Make sure you have Python installed.
3. Install the Streamlit library by running:
```bash
pip install streamlit
```
4. Run the app directly from your terminal:
```bash
streamlit run RecomandareFilme.py
```

---
*Note: This was a collaborative university team project. It was a great introduction to building data-driven apps quickly without needing to write HTML/CSS from scratch.*
