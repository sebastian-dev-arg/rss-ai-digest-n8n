# RSS AI Digest – Automated Tech News Pipeline

An end-to-end automation that collects, summarizes, and delivers the latest tech news using AI.

## Project Overview

- This project automates the process of consuming tech news by:

- Fetching articles from RSS feeds (Hacker News)

- Generating concise AI-powered summaries using Google Gemini

- Delivering a clean, formatted email digest with the top 5 latest articles

- Built as a fully automated workflow using n8n, this project demonstrates practical AI integration, workflow orchestration, and email automation.

## Tech Stack

- **n8n** – Workflow automation and orchestration

- **Google Gemini API** – AI-based content summarization

- **Gmail** – Automated email delivery

- **RSS Feeds** – News ingestion (Hacker News)

## Output Example
![Email recibido](email-resultado.png)

Automated email digest containing the 5 most recent tech news articles summarized by AI.

## Workflow Architecture

1. Schedule Trigger – Executes every hour

2. RSS Feed Read – Fetches articles from Hacker News RSS

3. Limit – Restricts processing to the latest 5 items

4. Edit Fields - Organize information 

5. Google Gemini – Generates AI summaries for each article

6. Code – Formats the content into responsive HTML

7. Gmail – Sends the email digest automatically

![Workflow](workflow-screenshot.png)

## Setup & Replication

To run this project in your own environment:

1. Import workflow.json into your n8n instance

2. Configure Gmail credentials

3. Generate a Google Gemini API key (free tier available)

3. Start receiving automated tech news digests every hour

## Use Cases

✅ Daily or hourly tech news digest

✅ Competitor and industry monitoring

✅ Automated content curation

✅ Client or internal newsletters

✅ AI-powered information pipelines

## Planned Improvements

 - [ ] Support for multiple RSS sources

 - [ ] Single daily digest instead of hourly emails

 - [ ] Keyword-based filtering

 - [ ] Slack and Discord integrations

## Author

Sebastian Agustin Saavedra Chavez - [LinkedIn](#)  | [GitHub](https://github.com/sebastian-dev-arg)


- Part of my automation and AI workflows portfolio built with n8n
