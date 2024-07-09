# Github-profile-viewer  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

<p align="center">
  <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Freshmaharidhas%2FGithub-profile-viewer&labelColor=%23000000&countColor=%230000ff&style=plastic&labelStyle=none"/>
  <img src="https://img.shields.io/github/repo-size/reshmaharidhas/Github-profile-viewer"/>
  <img src="https://img.shields.io/github/created-at/reshmaharidhas/Github-profile-viewer"/>
  <img src="https://img.shields.io/github/license/reshmaharidhas/Github-profile-viewer"/>
</p>
Desktop application to view profile data of Github users from their github username using the Github REST API.

![screenshot_my_profile](https://github.com/reshmaharidhas/Github-profile-viewer/assets/37250413/7fbd37d4-60a3-4010-ad21-748f87f80a83)

## Tech Stack💻
- Python
- Tkinter
- Matplotlib
- REST API

## API used💻
- GitHub REST API
- Endpoints:
    - /users/{username} (for user profile information)
    - /users/{username}/repos (for repository list)
    - /users/{username}/followers (for followers list)
    - /users/{username}/following (for following list)

## Features ✨
- Search github profiles 🔍
- Displays publicly available data in github profile such as,
    - Profile picture
    - Name
    - GitHub url
    - Bio
    - Email ID
    - Company
    - Location
    - Number of followers
    - Number of followings
    - Twitter profile name
    - Total number of repositories
    - Date of account creation in GitHub
    - Last date of GitHub account modified
- Display names of all repositories in the GitHub account.
- Opens the webpage of the repository in your default web browser by double clicking on the repository name.
- Displays the top 5 starred repositories in the Github account.
- Display all the followers and followings list.
- Graphical visualizations of GitHub profile repository 📊
    - Repository creation count over the years (Bar chart).
    - Programming language usage distribution (Pie chart).
    - Star count for top 5 repositories (bar chart).
    - Top committed repositories with commit count (pie chart).
- Error handling done to handle invalid github profiles, API rate limit exceeded.

## Screenshots💻
![screenshot_google](https://github.com/reshmaharidhas/Github-profile-viewer/assets/37250413/659ec57c-631a-4195-95e8-07b5af0296bb)

## Installation🔌
1. Clone the repository
2. Navigate to the project directory
3. Install the dependencies

## Run⚙️
Before running the application, 
1. Obtain a GitHub personal access token.
2. Insert your personal access token into github_profile_viewer.py file.
Replace with your GitHub personal access token
key = "YOUR_GITHUB_TOKEN'
3. Run the github_profile_viewer.py file.

## License 📖
MIT license
