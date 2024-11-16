---
title: "CodeHatari Blogging Hub"
slug: Software Engineering
category: projects
summary:
description:
cover:
  image: "images/carbon.png" 
  alt: "CodeHatari Blogging Hub"
  caption:
  relative: true
showtoc: true
draft: false
---

# Project Description

CodeHatari Blogging Hub is a platform designed to help developers share their knowledge, tutorials, and tips through blogging. Features user authentication and a responsive design. Integrates NewsAPI to provide users with the latest news articles.

# Technology and Architecture

## Frontend
- Vue.js 3: Used to building dynamic and responsive user interfaces. Vue's reactivity system allows for seamless data binding and component-based architecture.
- Nuxt.js: A framework built on top of Vue.js provides server-side rendering, static site generation, and a powerful configuration-based structure for efficient development.

## Backend
- FastAPI: Used it to build APIs with Python 3.10. We chose FastAPI because it ensures rapid development and high performance, making it an excellent choice for API development.
- SQLAlchemy: Used it to handle database operations providing a powerful and flexible database management solution.

## Intergration
Integrated `NewsAPI` into the blog pages to provide users with the latest news articles, enriching the blog content and ensuring up-to-date information is available.

## Containerization
To ensure consistent environments across development, testing, and production, Docker was used to containerize the application. Docker allowed for easy scalability and deployment of the application across different platforms.
It encapsulates the entire application in containers.

[Github Link](https://github.com/The-alpha-male/Codehatari-web_blog.git)
