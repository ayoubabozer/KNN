
# KNN Classification
[WIKI](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) In k-NN classification, the output is a class membership. An object is classified by a plurality vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.

in this project i will do simple exploration on an artificialy data,  
then the goal will be to evaluate use the KNN model to predict target class of the data set.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Docker
 
 ### Installing
 
 1. Copy the project to your machine
 
     ```
     git clone https://github.com/ayoubabozer/KNN.git
     ```
 
 2. Get into the KNN directory:
    
    ```
    cd KNN
     ``` 
 
 3. Pull & Run Docker Image
 
     ```
     docker run -d --rm --name jupyter -p 8888:8888 -v $PWD:/opt playniuniu/jupyter-pandas
     ```
     
 4. Open the app in : [http://localhost:8888](http://localhost:8888)


# ENJOY!.
