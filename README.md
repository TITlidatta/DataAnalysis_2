# GitHub User Data Scraper

This project is focused on scraping data from GitHub users located in Berlin, specifically those with more than 200 followers. The data is fetched using GitHub's REST API, and the responses are processed in JSON format.

## Project Overview

- **Goal**: To explore the correlation between the number of followers and the number of repositories for GitHub users in Berlin with more than 200 followers.
- **Method**: The GitHub API is queried using Python's `requests` library to obtain user data.
- **Key Insights**:
  1. **Followers vs. Repositories**: It was observed that GitHub users with the highest number of followers do not necessarily have a greater number of repositories. This suggests that follower count may not directly correlate with activity in terms of repository creation.
  2. **Email Importance**: Users who leave their emails empty on their GitHub profiles may miss opportunities for others to communicate with them regarding queries related to their repositories. It is recommended for developers to provide their contact details for better collaboration.

## Key Findings

- GitHub users with the highest number of followers may not have the largest number of repositories.
- Providing email addresses in profiles helps improve communication with collaborators and those who have questions related to your repositories.
