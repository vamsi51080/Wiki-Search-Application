# Wiki Search Application

This Wiki Search Application allows users to quickly search and retrieve articles from Wikipedia using an interactive and intuitive interface. The application is built with HTML, CSS, JavaScript, and Bootstrap for a responsive and user-friendly experience.

## Features

- **Real-Time Search**: The application lets users search Wikipedia articles by simply typing a query and pressing Enter.
- **Dynamic Results**: Search results, including the article title, description, and URL, are fetched and displayed dynamically without reloading the page.
- **Loading Spinner**: A loading spinner is displayed while the search results are being fetched, enhancing the user experience.
- **Responsive Design**: Built using Bootstrap, the application adapts to different screen sizes and devices.

## Technologies Used

- **HTML5**: Provides the structure and semantic elements of the application.
- **CSS3**: Custom styles and animations for a clean user interface.
- **Bootstrap 4**: Used for responsive design and layout.
- **JavaScript (ES6)**: Handles the dynamic behavior, fetching data from the Wikipedia API.
- **Wikipedia Search API**: Fetches search results based on the user's query.

## How It Works

1. Users type a search query in the input box.
2. When the Enter key is pressed, the app makes a request to the Wikipedia API to search for relevant articles.
3. Search results are displayed dynamically, including:
   - Article title (linked to the actual article)
   - Short description of the article
   - Article URL
   
4. A loading spinner is shown while the search is being processed to provide feedback to users.

## Installation and Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/wiki-search-app.git
   ```

2. Navigate to the project directory:
   ```
   cd Wiki-Search-Application/
   ```

3. Open the `index.html` file in your browser to use the application.

## Future Enhancements

- Add pagination to handle large search result sets.
- Implement advanced search filters (e.g., sort by relevance or date).
- Add auto-suggestions to enhance search functionality.
