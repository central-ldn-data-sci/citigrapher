# citigrapher

The citigrapher repository is a collection of successive weeks of meetups that look at a series of problems geared towards building a tool for deciding on optimum locations for people to meet within London - citigrapher.

Each week a new problem will be posed and an R and Python tutorial written in advance that will demonstrate one way in which a task may be completed. As we approach the end of citigapher we will form a development group who will continue the project outside of the meetups. 

---

### Citigrapher 1:

The first meetup looked at using google maps api to query travel distances from user provided postcodes to the nearest 3 tube stations. Solutions to this problem are provided within the citigrapher1 directories within each language directory. The solutions can be broken down roughly into 3 parts:

1. Ask the user for start and end postcodes for x number of people
2. How to then find the nearest y tubes to these postcodes
3. Using google distnace matrix API (https://developers.google.com/maps/documentation/distance-matrix/) to find out the walking travel time to these tubes.
