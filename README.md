# web-scraping-project
This project uses Python and Selenium to scrape popular topics, user details, replies, views, and timestamps from the Hugging Face discussion forum, automatically exporting the data into a structured CSV file. The collected data enables further analysis of user engagement and trending discussions.

This project involves automated web scraping of the Hugging Face discussion forum using Python and Selenium to systematically extract detailed information from forum threads. The scraping process retrieves popular topics, including titles, authors, reply counts, view counts, recent activity timestamps, and detailed content from individual posts within each topic.

The workflow starts by navigating through the main Hugging Face discussion page, automatically scrolling to load all available topic listings, and collecting metadata about each discussion. For every topic identified, the script visits the specific page to extract comprehensive data, including usernames, posting times (timestamps), and the content of each comment.

Finally, all extracted information is neatly structured and exported into a CSV file (forum_data.csv), allowing for subsequent data analysis and insights into user behavior, engagement trends, and popular discussion topics. This detailed scraping approach provides valuable datasets suitable for analytical reporting, sentiment analysis, user activity monitoring, and other data-driven insights.

