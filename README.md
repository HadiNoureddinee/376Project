# 376Project

# About the Project

In this assignment, we will develop a set of REST APIs capable of reading a JSON file deployed on a server and returning information by using a collection of simple HTTP requests invoked through Postman. I will be using the Java language to implement this project.

# Specifics

The RESTful APIs should be able to respond, with the appropriate data, to the following requests:

Get all tweets (create time, id, and tweet text) available in the archive.
Get a list of all external links (all links that appear in the tweet text field. Use regular expressions to extract the links, the links should be grouped based on tweet ids.
Get the details about a given tweet (given the tweet’s id). Details of the tweet include created_at, text, screen_name, lang.
Get detailed profile information(name, location, description) about a given Twitter user (given the user’s screen name).

# Installation

1.Download The Eclipse Spring Boot Suite depending on your specific console:

    https://spring.io/tools
   

# Usage

You can connect to the API using Postman on  http://localhost:8080


# Rest API Basic

There are 4 general commands the can be used in a REST API:
    GET - Retreive a resource
    PUT - Update a resource
    POST - create a new resource
    Delete - Deleting a resource
