# Featmap Docker
This repository runs an instance of [Featmap](https://github.com/amborle/featmap) in Docker with an accompanying postgres instance. The postgres data is stored in the same folder that the image is run in a directory called `data`.

To run it:

1. Clone this repository:
    ```
    git clone https://github.com/CogsAndGears/featmap-docker.git
    ```
2. Make sure you have docker-compose installed (via [docker desktop](https://www.docker.com/products/docker-desktop/) or otherwise), cd into the root of this directory, and run:
    ```
    docker-compose up
    ```
3. Once the images are done downloading and have been started, featmap should be available on: [http://localhost:5000](http://localhost:5000)

