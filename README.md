# Introduction

This project is a Movie Review Website developed using Express, a popular web application framework for Node.js. The primary objective of this project is to demonstrate the containerization of applications with Docker and deploy them in the cloud. Docker allows for easy and consistent deployment across various environments, making it an ideal choice for web applications.

# Features

- Movie Reviews: Users can read and submit movie reviews.
- Rating System: Users can rate movies and view the overall rating.
- Sentiment Analizer: This site uses AI to detect review sentiment.

# Requirements

- Need NLU API Key and URL from IBM Cloud to run the sentiment analysis.
- Need Cloudant API Key and URL from IBM Cloud to run the database.

You can get the API Key and URL from IBM Cloud by creating a new service for each one.

You can see the format of the data you need in the file .env.sample.
Looks similar to this:

```env
CLOUDANT_URL=https://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx-bluemix.cloudantnosqldb.appdomain.cloud
CLOUDANT_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
NLU_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
NLU_URL=https://api.us-south.natural-language-understanding.watson.cloud.ibm.com/instances/xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
```

## To run the Movie Review Website locally, follow these steps:

Install Docker on your machine: [Docker Installation Guide ](https://docs.docker.com/engine/install/)

- Clone this repository:

```

git clone https://github.com/BrayanDH/Movie-Reviews-Database.git

```

- Navigate to the project directory:

```

cd Movie-Reviews-Database

```

- Build the Docker container:

```

docker build -t movie-review-website .

```

- Run the container:

```

docker run -p 8080:8080 movie-review-website

```

Open your web browser and visit http://localhost:8080 to access the Movie Review Website.

To run the Movie-Reviews-Database locally without docker, follow these steps:

1. Clone this repository:

   ```
   git clone https://github.com/BrayanDH/Movie-Reviews-Database.git
   ```

2. Navigate to the project directory:

   ```
   cd Movie-Reviews-Database
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Start the server:

   ```
   npm start
   ```

5. Open your web browser and visit http://localhost:8080 to access the Movie-Reviews-Database API.

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
