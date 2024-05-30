Project Introduction:
The NBA Stats Breakdown project is an initiative to create a comprehensive and user-friendly application that retrieves, displays, and stores the latest basketball game scores and player statistics from the NBA. The project leverages the "balldontlie.io" API to access real-time data and presents it in a readable and accessible format for basketball enthusiasts and analysts.

Project Description:
The application is designed to extract data on recent NBA games, including team scores, and individual player stats such as names, teams, positions, heights, and weights. The data is fetched and processed using Python scripts that handle API interactions and manage potential exceptions. The final output is displayed in the console and saved to JSON files for persistent storage or further analysis.

Features:
- Fetching real-time NBA scores and player statistics.
- Error handling to manage network issues or API changes.
- Console output for immediate readability of the latest stats.
- Data persistence by saving the information to JSON files.
- Scalability to include additional stats or features in the future.

Project Breakdown (5 Days):

Day 1: Project Setup and API Exploration
- Set up the Python development environment.
- Explore the "balldontlie.io" API documentation.
- Write initial functions to test API connectivity and data retrieval.
- Outline the structure of the console output for displaying data.

Day 2: Data Fetching and Processing
- Implement `get_scores()` and `get_player_stats()` functions to fetch the required data.
- Process the API response to extract and format the relevant information.
- Create a basic error handling mechanism for network and API response issues.

Day 3: Data Display and User Interface
- Develop the `display_scores()` and `display_player_stats()` functions to output the data to the console.
- Format the console output for better readability.
- Test the display features with various data points to ensure clarity and accuracy.

Day 4: Data Persistence
- Write the code to save the fetched scores and player stats to JSON files (`scores.json` and `players.json`).
- Implement exception handling for file operations.
- Test the file saving feature to ensure data is correctly written and stored.

Day 5: Code Review and Testing
- Conduct a thorough code review to optimize and refactor where necessary.
- Test the entire application for any bugs or issues.
- Document the code and usage instructions.
- Prepare the project for potential deployment or distribution.
  
