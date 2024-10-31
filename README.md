# TDS_Project

- **Data Collection**: We used the GitHub API to scrape data on users in Melbourne with over 100 followers and collected details about each user and their repositories.
- **Interesting Finding**: JavaScript is the most popular language among top GitHub users in Melbourne, showing strong community preference for this language in development.
- **Recommendation**: Developers aiming to grow their GitHub following should engage in JavaScript-based open-source projects, which may resonate more with the local developer community.

## Overview

This project gathers and analyzes GitHub data for users based in Melbourne with over 100 followers, focusing on user profiles and repository attributes. The analysis explores trends in programming languages, popular licenses, and community engagement to provide insights for developers aiming to improve their visibility and influence.

## Data Collection

Using GitHub's API, we retrieved user profiles based in Melbourne with follower counts exceeding 100. For each user, we collected profile information and up to 500 of their most recently pushed repositories, capturing details such as programming languages, stargazers, watchers, and license types.

## Analysis and Findings

After analyzing the data, we discovered several key insights:
- **Programming Language Preference**: JavaScript is the most popular language among Melbourne’s most-followed developers, indicating a strong preference within the community.
- **License Popularity**: The most common licenses used by these developers are MIT, Other, and Apache-2.0.
- **Community Engagement**: Most of the prominent developers are associated with open-source projects, indicating a collaborative approach to development.
- **Company Affiliation**: The majority of developers are associated with Monash University, showing academic interest and involvement in open-source projects.
- **Followers and Public Repos Correlation**: There is a slight positive correlation (0.188) between the number of followers and the number of public repositories, suggesting that creating more repositories might slightly improve follower count.
- **Bio Length**: Developers who write longer bios tend to have more followers, with each additional word in a bio potentially contributing to about 7.352 more followers on average.

## Recommendations for Developers

Developers looking to enhance their GitHub presence should consider contributing to JavaScript open-source projects, as JavaScript is highly popular among Melbourne’s developer community. Engaging in such projects can increase visibility and create connections with other professionals in the area.

## Files in Repository

- `users.csv`: Contains data on each Melbourne-based GitHub user with over 100 followers, including profile details and metrics.
- `repositories.csv`: Includes up to 500 repositories per user, detailing the programming language, star count, and additional repository information.
- `README.md`: Documentation for the project, including data collection methods, insights from analysis, and recommendations.
