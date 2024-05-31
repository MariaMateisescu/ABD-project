# ABD-project
The goal of the project is to assess the MongoDB database skills of the student. The project has a medium difficulty level and is relevant to industry employers of today.

Prerequisites:

Download the latest US Zips dataset from https://simplemaps.com/data/us-zips (choose the free tier). The dataset has approximately 33k entries.
Create a MongoDB instance. You may use your own MongoDB Atlas instance in cloud or use a local instance. For local instances Docker is preferred, but you may also choose to install MongoDB as a standalone server on your OS.
Import the dataset into the MongoDB instance.
Requirements:

a) Get the states with a total population of over 10 million.

b) Get the average city population by state.

c) Get the largest and the smallest city in each state.

d) Get the largest and the smallest counties in each state.

e) Get the nearest 10 zips from one of Chicago's landmarks, the Willis Tower situated at coordinates 41.878876, -87.635918.

f) Get the total population situated between 50 and 200 kms around New York's landmark, the Statue of Liberty at coordinates 40.689247, -74.044502.

Notes:

Create the indexes you deem relevant for your collection. You will be asked on the performance of your indexes so be prepared to defend your choice, preferably by analyzing the execution statistics.
For requirements e) and f), you may add a geo field to your collection in order to leverage geospatial query operators.
