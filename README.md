# Google Search Website

This project is a simple replica of Google's search functionality, including regular search, image search, and advanced search pages. The website follows Google's own CSS aesthetics and behavior.

## Features

1. **Three Pages**:
    - **Regular Google Search** (`index.html`): Main search page.
    - **Google Image Search**: Page for image searches.
    - **Google Advanced Search**: Page for advanced search options.

2. **Navigation Links**:
    - The Google Search page has links in the upper-right corner to navigate to Image Search and Advanced Search.
    - The Image Search and Advanced Search pages have a link in the upper-right corner to navigate back to the Google Search page.

3. **Google Search Functionality**:
    - The user can type a query, click “Google Search”, and be taken to the Google search results page for that query.
    - The search bar is centered with rounded corners, and the search button is centered beneath the search bar.

4. **Google Image Search Functionality**:
    - The user can type a query, click the search button, and be taken to the Google Image search results page for that query.

5. **Google Advanced Search Functionality**:
    - The user can provide input for the following four fields:
        - Find pages with… “all these words:”
        - Find pages with… “this exact word or phrase:”
        - Find pages with… “any of these words:”
        - Find pages with… “none of these words:”
    - The options are stacked vertically, and the text fields are left-aligned.
    - The “Advanced Search” button is blue with white text.
    - Clicking the “Advanced Search” button takes the user to the search results page for their given query.

6. **I'm Feeling Lucky Button**:
    - The main Google Search page includes an “I’m Feeling Lucky” button.
    - Clicking this button takes users directly to the first Google search result for the query, bypassing the normal results page.

## Project Structure

- **index.html**: Main Google Search page.
- **image_search.html**: Google Image Search page.
- **advanced_search.html**: Google Advanced Search page.
- **static/css/style.css**: CSS file for styling the pages.