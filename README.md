# LeetMetric

A lightweight web application that displays a user's LeetCode problem-solving statistics using the LeetCode GraphQL API. Users can enter a LeetCode username and instantly view solved problems categorized by difficulty along with submission statistics.

## Features

- Search any public LeetCode profile
- Displays solved problems by difficulty:
  - Easy
  - Medium
  - Hard
- Shows:
  - Total solved problems
  - Total submissions
  - Easy submissions
  - Medium submissions
  - Hard submissions
- Clean and responsive user interface
- Circular progress indicators for each difficulty level

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- LeetCode GraphQL API

## Project Structure

```
LeetMetric/
│── README.md
│── index.html
│── index.js
│── style.css
```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/LeetMetric.git
```

2. Open the project folder.

3. Run the project using Live Server (VS Code) or any local server.

4. Enter a valid LeetCode username.

## Note

The application retrieves data from LeetCode's GraphQL API. During development, a CORS proxy is used because browsers restrict direct cross-origin requests to the GraphQL endpoint.

## Future Improvements

- Better responsive UI
- Dark/Light mode
- User profile details
- Contest rating integration
- Recent submissions section
- Submission charts
- Error handling improvements

## Author

Divya Sharma
