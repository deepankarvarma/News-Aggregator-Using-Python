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

The app uses the NewsAPI to fetch news articles based on the user's selection of country and category. The API key is stored securely using the `secrets` feature of Streamlit.

The user can select a country from the dropdown list on the left-hand side of the app. The available options are based on the countries supported by the NewsAPI. The user can also select a category from the dropdown list to filter the news articles by topic.

If the user selects "All" as the category, the app fetches all the top headlines from the selected country. If a specific category is selected, the app fetches the top headlines for that category in the selected country.

The app then displays the news articles on the right-hand side of the app. For each article, the title is displayed as a heading and the URL of the article is displayed as a clickable link.

## How to customize the app

You can customize the app by changing the list of countries and categories available in the dropdown lists. To do this, simply modify the `countries` and `categories` lists in the code.

You can also modify the styling of the app by changing the CSS in the `style` tag in the code. The current background image is set using the `background-image` property.

## Conclusion

This News Aggregator app is a simple example of how to use the NewsAPI and Streamlit to build an interactive web application. With some modifications, you can use this app as a starting point to build your own news aggregator or any other web application that requires fetching data from an API.
