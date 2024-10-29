# GitHub Moscow Developers Analysis

* Data was scraped using GitHub's REST API v3, searching for users in Moscow with over 50 followers and their repositories, implementing rate limiting and pagination to ensure complete data collection.

* The most interesting finding is that Python is the most commonly used programming language among Moscow developers with high follower counts, followed by JavaScript and Go.

* Developers should consider adding detailed project documentation and wikis to their repositories, as the analysis shows that repositories with wikis tend to attract more stars and watchers.

## Files
- `users.csv`: Contains information about GitHub users in Moscow with over 50 followers
- `repositories.csv`: Contains details about these users' public repositories
- `github_scraper.py`: The Python script used to collect and analyze the data

## Usage
1. Replace `YOUR_GITHUB_TOKEN_HERE` with your GitHub personal access token
2. Run the script to collect data
3. The script will generate CSV files and analysis results

## Note
This data was collected in accordance with GitHub's API terms of service and rate limiting guidelines.
