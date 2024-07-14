#Overview
This README provides information about the News API hosted at https://newsserver-bsja.onrender.com/api/news. This API fetches 5 random news articles and is easily accessible for integration into your projects.

Features
Fetch Random News: Retrieve 5 random news articles with each request.
Hosted and Accessible: The API is hosted on Render, ensuring reliability and availability.
Endpoint
GET /api/news
Fetch 5 random news articles.

URL: https://newsserver-bsja.onrender.com/api/news

Method: GET

Response: A JSON array containing 5 random news articles. Each article object includes the following fields:

title: The title of the news article.
description: A brief description of the news article.
url: The URL to the full news article.
publishedAt: The publication date of the news article.
source: The source of the news article.
