# Introduction

This project is a Movie Review Website developed using Express, a popular web application framework for Node.js. The primary objective of this project is to demonstrate the containerization of applications with Docker. Docker allows for easy and consistent deployment across various environments, making it an ideal choice for web applications.

# Features

- Movie Reviews: Users can read and submit movie reviews.
- Rating System: Users can rate movies and view the overall rating.
- User Authentication: Secure user authentication to manage reviews and ratings.

## To run the Movie Review Website locally, follow these steps:

Install Docker on your machine: [Docker Installation Guide ](https://docs.docker.com/engine/install/)

- Clone this repository:

  `git clone https://github.com/BrayanDH/Movie-Reviews-Database`

- Navigate to the project directory:

  `cd Movie-Reviews-Database`

- Build the Docker container:

  `docker build -t movie-review-website .`

- Run the container:
  `docker run -p 3000:3000 movie-review-website`

Open your web browser and visit http://localhost:3000 to access the Movie Review Website.

# Dependencies

The Movie Review Website utilizes the following dependencies:

- Express
- Cloudant
- EJS (Embedded JavaScript) templating engine
- Docker
  Please refer to the package.json file for the complete list of dependencies and their versions.

# Contributing

Contributions to the Movie Review Website are welcome! Feel free to open issues or submit pull requests.

# License

This project is licensed under the MIT License.

# Acknowledgments

Special thanks to the creators and maintainers of the libraries and frameworks used in this project.
