# News Aggregator using NewsAPI and Streamlit

This is a simple web application that aggregates news articles from various sources using the NewsAPI and displays them in one place. It allows users to filter news by country and category.

## How to use the app

1. Go to the [app link](https://deepankarvarma-news-aggregator-using-python-app-ad4qel.streamlit.app/) in your web browser.
2. Select a country from the sidebar. The available options are US, GB, IN, CA, AU, FR, DE, JP, CN, RU, BR, MX, IT, ES, and KR. 
3. Optionally, select a category from the sidebar. The available options are All, Business, Entertainment, General, Health, Science, Sports, and Technology.
4. Click on the "Submit" button to fetch the news articles.
5. The app will display the news articles from the selected country and category.

## Dependencies

- `streamlit`: A Python library for building interactive web applications.
- `requests`: A Python library for making HTTP requests.

## How to install the dependencies

1. Install Python 3.7 or higher on your system.
2. Install `streamlit` and `requests` using pip: `pip install streamlit requests`.

## How to run the app locally

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Run the command: `streamlit run news_aggregator.py`.
4. The app will be launched in your default web browser.

## How the app works

This app uses the NewsAPI to fetch news articles from various sources. It allows the user to filter the news by country and category. The user can select a country from a list of available countries, and optionally select a category from a list of available categories. The app then makes a request to the NewsAPI with the selected country and category as parameters, and returns the news articles as a JSON response.
