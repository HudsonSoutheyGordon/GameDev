# GameDev
A collection of the games I have worked on: forestree. Wi2ards, Desert Drift, and Air-O-Space

This repo is an overview of each of my gamedev projects. Unfortunately, I cannot host the source code for these out of respecting my teammates wishes, and contractual obligations but I still think it is worth demonstrating them here for my portfolio. If you are an interested collaborator or potential employer, I would be happy to share elements of the code privately.

# forestree.
---
My first full fledged release which I solo-developed, and was released in partnership with (tentree)[https://www.tentree.com/].
As I've stated elsewhere in my profile, I am deeply passionate about how software can be a tool for social good. I decided to integrate this passion with my long-time hobby of game development to create a charity-forward game-dev studio: (Give Grow Games.)[givegrow.games] The idea is that each game we make has philanthropy integrated into its DNA.

forestree. is a mobile puzzle game centered around planting trees both virtually and around the world! Strategically build the ultimate ecosystem by placing wildlife and plant life across unique biomes.

![Playing the Game](Images/forestree/forestree_forest.gif)

#### Biggest Development Challenge
This was my first large-scale project. I went into it incredibly naively. My file structure was poor, and I was not as concerned about accruing technical debt as I should have been. This was fine for 90% of the project, but refactoring for performance in the final sprint was a nightmare. Eventually, I did succeed and I'm proud of the performance I was able to achieve with it.

#### Biggest Development Success
One thing I was really worried about with a grid-based game was a performant solution for pathfinding and checking the board status each turn. After some experimentation, I was able to use a breadth-first-search algorithm tailored to my game which worked incredibly well. In fact, I think I this algorithm's performance and how it is completely undetectable in gameplay is my proudest technical achievement with this game.

#### Summary of Lessons Learned
* Version control is vital; the peace of mind it brings is worth its weight in gold.
* Spend the time upfront to make a good filestructure, it pays dividends in the home-stretch of the project.
* Refactor early; refactor often.
