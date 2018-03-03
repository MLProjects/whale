# Humpback whale challange
Welcome to the Humpback Whale Identification Challenge a [Kaggle](https://www.kaggle.com) competition.
# Description
>After centuries of intense whaling, recovering whale populations still have a hard time adapting to warming oceans and struggle to compete every day with the industrial fishing industry for food.
To aid whale conservation efforts, scientists use photo surveillance systems to monitor ocean activity. They use the shape of whales’ tails and unique markings found in footage to identify what species of whale they’re analyzing and meticulously log whale pod dynamics and movements. For the past 40 years, most of this work has been done manually by individual scientists, leaving a huge trove of data untapped and underutilized.
In this competition, you’re challenged to build an algorithm to identifying whale species in images. You’ll analyze Happy Whale’s database of over 25,000 images, gathered from research institutions and public contributors. By contributing, you’ll help to open rich fields of understanding for marine mammal population dynamics around the globe.
We'd like to thank Happy Whale for providing this data and problem. Happy Whale is a platform that uses image process algorithms to let anyone to submit their whale photo and have it automatically identified.

# Project structure
- data <- the raw data used for this project goes here.
-- trainimages <- uncompressed training images go here
- src <- the source code goes here

# Run the code
This project is available within a docker [here](https://hub.docker.com/u/tomasarrufat/)
```sh
$ docker run -it -p 8888:8888 tomasarrufat/whales:latest
```
Go to your browser on http://localhost:8888/