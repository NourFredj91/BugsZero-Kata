# Class Game
1. Modify the Class Game in order to contain only fields (players, places,...)  and constructor
2. remove the "for" inside the constructor
3. remove all methods in Game class to another class called GameService (under package called services). 
4. change the package name from uglytrivia to model for example
5. add setters and getters

# Interface GameService
1. 
# Class GameSerivce
1. delete unused methods like isPlayable
2. change the return of method "add" to void because we don't use it
3. currentCategory : change "if" to switch case
4. delete useless system.out and use log.info instead 
5. change createRockQuestion to be generic createQuestion(String message, int index)

# Class GameRunner
1. modify method playGame to use While and not do While

# file pom.xml
1. change the version of junit