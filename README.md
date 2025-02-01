# Web Crawler Project

A Node.js web crawler that analyzes internal links on websites.

## Features

- Crawls web pages recursively starting from a base URL
- Extracts and normalizes URLs from HTML content
- Tracks internal link counts between pages
- Generates a report showing most linked pages

## Key Components
  - crawl.js - Core crawling logic and URL handling
  - report.js - Report generation
  - main.js - CLI entry point

## Technologies
  - Node.js
  - Jest for testing
  - JSDOM for HTML parsing
  - Native fetch API for HTTP requests
