# Mini Google 1998

A fun, beginner-friendly search website for a first-year AI lab. It compares two ways to rank search results: counting how often a word appears in a page, and estimating PageRank with a random surfer simulation.

## Features

- Search sample web pages about food and pizza in Pune.
- Compare results side by side:
  - **Old way:** ranks pages by how often the search word appears in their text.
  - **PageRank way:** ranks matching pages by estimated PageRank.
- Estimates PageRank with a 100,000-move random surfer simulation and a 15% random-jump chance.
- Shows each result’s URL and score.
- Ignores capital letters when searching.
- Uses one file with plain HTML, CSS, and JavaScript.

## Run it

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Enter a word such as `pizza`, then click **Search**.

No installation or server is required.

## Sample data

The website includes six sample pages about Pune food, college canteen reviews, and pizza. Each page has text and links to other pages in the sample set.

## Built with

- HTML
- CSS
- Vanilla JavaScript
