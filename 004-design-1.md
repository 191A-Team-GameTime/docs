#Software Design

## Team GameTime

1. Java for the functionality and UI, jQuery for the database calls 
2. We will be building off of the preexisting M2Catalyst SDK
3. We will also use the Facebook API to allow for connection through Facebook as well as its social media purposes.
4. The pre-existing SDK will be used for a majority of the functions within m2GameTime. The Facebook and Twitter APIs will support social media interaction.
5. MVC
6. Data from each user’s phone on game usage (names, times, location) collected by the M2Catalyst SDK
7. The database is a relational model. Things to be stored in database: User IDs, Game IDs, Location, Timed Information
8. The models in our project are our database "objects", the USER object will store user name, age, list of games, and list of friends (other users). The GAME object will store the title, developer, publisher, etc. The controllers are the things users can manipulate the data, which will simply be to download and play games, challenge other users, etc. All of this information will be displayed in a friendly, intuitive and minimalistic user interface. 
