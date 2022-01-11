# GameDev
A collection of the games I have worked on: forestree. Wi2ards, Desert Drift, and Air-O-Space

This repo is an overview of each of my gamedev projects. Unfortunately, I cannot host the source code for these out of respecting my teammates wishes, and contractual obligations but I still think it is worth demonstrating them here for my portfolio. If you are an interested collaborator or potential employer, I would be happy to share elements of the code privately.

# forestree.
---
My first full fledged release which I solo-developed, and was released in partnership with (tentree)[https://www.tentree.com/].
As I've stated elsewhere in my profile, I am deeply passionate about how software can be a tool for social good. I decided to integrate this passion with my long-time hobby of game development to create a charity-forward game-dev studio: (Give Grow Games.)[givegrow.games] The idea is that each game we make has philanthropy integrated into its DNA.

forestree. is a mobile puzzle game centered around planting trees both virtually and around the world! Strategically build the ultimate ecosystem by placing wildlife and plant life across unique biomes.

<p align="center">
    <img src="Images/forestree/forestree_forest.gif" alt="Playing the Game" width="300"/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <img src="Images/forestree/forestree_menu.gif" alt="I love my menu!" width="300"/>
</p>

---
#### Biggest Development Challenge
This was my first large-scale project. I went into it incredibly naively. My file structure was poor, and I was not as concerned about accruing technical debt as I should have been. This was fine for 90% of the project, but refactoring for performance in the final sprint was a nightmare. Eventually, I did succeed and I'm proud of the performance I was able to achieve with it.

#### Biggest Development Success
One thing I was really worried about with a grid-based game was a performant solution for pathfinding and checking the board status each turn. After some experimentation, I was able to use a breadth-first-search algorithm tailored to my game which worked incredibly well. In fact, I think I this algorithm's performance and how it is completely undetectable in gameplay is my proudest technical achievement with this game.

#### Some of the Lessons Learned
* Version control is vital; the peace of mind it brings is worth its weight in gold.
* Spend the time upfront to make a good filestructure, it pays dividends in the home-stretch of the project.
* Refactor early; refactor often.

# Wi2ards
---

Wi2ards was made in 48 hours for the GMTK Game Jam 2021. I was on a team with 3 others: [Ryan Dotsikas](https://github.com/RyanDotsikas), [James Tugman](https://www.jtugman.com/), and Niki Non. It was our second time working together all as a team and we had the incredible good fortune of finishing in the top 1.2% of participants; considering this was the biggest game jam in history, we are thrilled with this result! I acted as co-developer on the project and led development of the VFX systems used in the game.

The theme for the Game Jam was "Joined Together" and so Wi2ards is a small action game about using magic to string together enemies to make big combos.

<p align="center">
    <img src="Images/Wi2ards/wi2ards.gif" alt="Playing the Game" width="300"/>
</p>

---

#### Biggest Development Challenge
Debugging. In a 48 hour game jam, we often don't have the ability to plan our software architecture as well as we would like, and often this can of course lead to bugs. We had two major bugs arise during development, one of which we solved in time, the other we fixed after. The first bug, is the more interesting of the two: The game would sometimes throw a game-breaking error seemingly at random. Eventually we isolated the bug: when conneting enemies, our hitbox accidently lingered, ruining the linearity of the how we chained the enemies. Since the buggy hitbox was disjointed from our character sprite (and was thus invisible) it was incredibly hard to isolate. Eventually, some clever enabling/disabling of the hitbox proved a sufficient solution in the short time frame.

#### Biggest Development Success
I try not to be a results-oriented person when judging the success of my projects. I do honestly believe lessons learned and skills gained trump results every time, but it is hard for me to ignore the success of this project. Game Jams are actually how I began my Software Development career, and nearly a decade ago, I used to look at the top 100 finishers and wonder how they pulled it off; so it is humbling and gratifying to have achieved that level of success with my team on this project.

#### Some of the Lessons Learned
* Polish makes all the difference! This is the first game we really invested in VFX and I really believe it was crucial to the project's success.
* Sometimes, when in a time-crunch, great is the enemy of good
* Enemy AI is hard!
