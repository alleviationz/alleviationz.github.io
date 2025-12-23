layout: page
title: "Alec's ePortfolio"
permalink: https://alleviationz.github.io/Databases

# Databases

# AAC animals Database w/ NoSQL

# Narrative:
This artifact is from my final project in client-server development CS340. It's a noSQL database that allows basic CRUD functionality to manipulate retrieved animal data. The animals are categorized by numerous attributes including breed, name, age, etc.
The original artifact used a local MongoDB Compass database with hard-wired connection variables. It also contained a radio selector to pick between a few animal attribute types and categorize the data. In this project, I originally intended to
migrate to an AWS cluster, but I was unable to create any clusters (possibly due to the age of my account). I migrated to MongoDB's cloud MongoAtlas, instead, which uses the same setup that AWS would have anyways.
I cleaned up some of the old code and tests, refactoring tests into automated unit tests. The radio selector was replaced with a drop-down that allows selection of various attributes (similarly to the previous implementation), but
it also incorporates a search bar that updates as the user types. 
The security could be improved further by implementing better try-catch blocks, resolving the initial "None"-loading error that is meant to default to breed categorization, and implementing
some better security. Additionally, the previous markers could be replaced with indices, assuming they will be searched often.

# Purpose
The purpose of this enhancement was to provide a better user experience with the search functionality because the radio-selector had strong limitations.


# Search w/ drop-down selector
![Search bar drop-down selector](https://github.com/user-attachments/assets/4adeec4e-fc74-4b71-b119-248ef9a18748)
![Second image of drop-down selector](https://github.com/user-attachments/assets/ebd96904-01f1-4a4b-bd44-cf2656121ad4)


# Resulting Graph
![Graph after drop-down was selected](https://github.com/user-attachments/assets/1e0e57b9-20a3-4e01-bd2a-06c666a615d5)


# Results update as user searches
![Graph update during user search](https://github.com/user-attachments/assets/d2ceea34-959c-4301-9e20-b251a547bff0)
![Second image of graph](https://github.com/user-attachments/assets/86de1293-6391-4416-b4d0-ef6eb1279550)


# Migration to MongoAtlas w/ environment variables to obfuscate credentials
![MongoAtlas migration](https://github.com/user-attachments/assets/9af7c92f-df2b-46b3-8f44-6ecc729006f2)


# Unit Tests
![Unit tests](https://github.com/user-attachments/assets/ba1067b9-346d-44f3-8ea7-c8c0a347026e)


# Full Project repo
[Full Project](https://github.com/alleviationz/CS-340-Client-Server_Development)






