# URL Shrinker

URL Shrinker is a Node.js backend project that uses the Express.js framework to compress and share lengthy URLs. It provides a simple API for generating unique short URLs, allowing users to easily share and track their usage. The application is designed to be scalable, user-friendly, and customizable, making it an effective solution for managing and simplifying URLs in various scenarios.

## Live-Demo

<a href="https://www.youtube.com/watch?v=XVDuomkMOgM">https://www.youtube.com/watch?v=XVDuomkMOgM</a>


## Technologies

<div align="left">
<img alt="HTML" src="https://img.shields.io/badge/html-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
<img alt="CSS" src="https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/> 
<img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img alt="NodeJS" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white"/>
<img alt="ExpressJS" src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB"/>
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img alt="Bootstrap" src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/>
</div>


## Features

- Shortens long URLs into compact and shareable links.
- Customizable short link generation for personalized URLs.
- Automatically redirects users to the original long URL.
- Provides usage statistics to track link popularity and engagement.


## Architecture

The URL Shrinker backend follows a simple and scalable architecture, leveraging the popular Node.js runtime and Express.js framework for handling HTTP requests and responses. The application interacts with a MongoDB database to store information about the shortened URLs and their associated long URLs, as well as the click count for each shortened link. 

To ensure unique and random short IDs for the shortened URLs, the project uses the ShortId library. The design is kept stateless to facilitate easy scalability and deployment in distributed environments.



