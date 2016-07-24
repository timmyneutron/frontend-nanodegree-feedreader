# Udacity Front-End Web Developer Nanodegree
# Project #5: Feed Reader

### Introduction
This is a project for Udacity's Front-End Web Developer Nanodegree. In it, I was given an already-completed app that displays titles and snippets from several RSS feeds, and my task was to write test suites for this app using Jasmine.
### Concepts
Concepts explored in this project include:

  - test-driven development
  - constructing test suites using Jasmine

### Getting Started
To get started, follow these steps:

1. Download/clone the repository
2. To run the app, open ```index.html``` in a web browser
3. To inspect the tests, open ```jasmine/spec/feedreader.js```

### Instructions
1. The app will load with a list of titles of articles from one of its RSS feeds. Click on a title to view that article.
2. To change RSS feeds, click the hamburger icon in the top left corner to open the sidebar menu, and select a new feed.
3. Jasmine should indicate at the bottom that the app is working as it should

### Tests
Jasmine tests were written to show that:
1. The list of feeds is defined
2. All feeds have URLs associated with them
3. All feeds have titles
4. The sidebar menu is hidden by default
5. Clicking the hamburger button toggles the menu
6. There's at least one article entry after a feed has loaded
7. The content changes when you select different feeds
