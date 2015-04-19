# Min_Duan_CSCI2270_FinalProject
Michael Min, Qiu Duan's, and Michael Xiao's Final Project CSCI2270. This project is made to simulate the matchmaking 
system of the game League of Legends, made by Riot Games. For every game of League of Legends, two teams of five
players are required, resulting in 10 players who need to be found. However, these players also must be of roughly 
equal skill level, which is determined by their individual match-making rating (MMR). MMR is determined by a series
of factors, such as the number of losses, wins, and other statistics of a certain player, and players of similar MMR
are placed in games together by the system. In this project, we intend to simulate the queue of the matchmaking
system by first calculating MMR given by a player's input data. Then, using a binary search tree that will store and
sort players based on MMR, players will be kept inside until 10 players of similar MMR have been found. After that,
those 10 will be removed from the tree and the process will continue for as long as player data is put into the
queue.
