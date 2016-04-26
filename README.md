# Unofficial filmaffinity API

## REST API
The REST API provide programmatic access to read data from Filmaffinity.com in spanish using [filmaffinity gem](https://rubygems.org/gems/filmaffinity).

## Features
 - **GET** ```/api/top```
 Returns an array with Top 30 movies, just including ```id``` and ```title```

 - **GET** ```/api/search?q=query```
 Returns an array with movies that includes your query in the movie title, just including ```id``` and ```title```

 - **GET** ```/api/movie/:id```
 Returns an object that contains full movie data

## Feedback and contribution
If you find any issues with the API or you want to contribute, please use this github repository.
