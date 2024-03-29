# capstone-personal-site

[Check out the live site here!](https://m311han.github.io/capstone-personal-site/)

## Description

Capstone Personal Site is a four-page website where I share personal information, hobbies, favourite recipes, and a saved items feature. The website is primarily designed for those who share similar interests and would like to know more about me, my childhood and my favourite recipes. It also offers a feature for users to save articles, images, links, and information for viewing at a later time.

## Table of Contents

- [Installation](#installation)
- [Containerisation](#Containerisation)
- [Usage](#usage)
- [Credits](#credits)

## Installation

Follow the steps below to install, configure, and get the project running locally on your system. You just need to clone the repository, navigate into the repository's directory, and then open it with a live server. Here are the steps you would follow:

```bash
# Open a terminal

# Clone the repository by typing:
git clone https://github.com/M311HAN/capstone-personal-site.git

# Navigate into the cloned directory with:
cd capstone-personal-site

# Open with live server (you need to have Live Server extension installed on your code editor) If you are not using VS Code or don't have the "Live Server" extension, you can simply open the index.html file with any web browser to view the website.
```

## Containerisation

This project also comes with a Dockerfile that can be used to containerise the application. This allows for a consistent environment and easy deployment across different systems. To run the site within a Docker container, follow these steps:

```bash
# Make sure Docker is installed on your system.

# Build the Docker image:
docker build --platform linux/amd64 -t melihhan/my-website:amd64 .

# Run the Docker container:
docker run -d -p 80:80 melihhan/my-website:amd64
```
This will start the website inside a Docker container, and it can be accessed via a browser at http://localhost:80 .
 
## Usage

The Capstone Personal Site can be used to learn more about me and my favourite recipes. It provides a platform where users can save articles, images, links, or any other information they find interesting. Users can interact with the website by liking posts and leaving comments on the pages. They can also subscribe to a newsletter for receiving more recipes.

For example, to save an article, simply click on the save button on any article and it will be moved to the 'Saved Items' page. This page can be viewed later to recall saved articles.

## Credits

This project was created by Melihhan (https://github.com/M311HAN).
