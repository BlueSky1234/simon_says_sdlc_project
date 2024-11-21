**User Stories and Acceptance Criterion Frame**

**Title**: Each user story gets a brief name   
**As a \[type of user\],**  
	•	Who is the user or role you’re focusing on? (e.g., player, admin, guest)  
**I want to \[do something\],**  
	•	What is the user trying to do or accomplish? (e.g., “save my game progress,” “choose a character”)  
**So that \[I can achieve a goal or benefit\].**  
	•	Why is this important for the user? What benefit or outcome will the user get from this feature? (e.g., “so I can continue my game later,” “so I can play as my favorite character”)

**Acceptance Criteria** (used to build the Definition of Done)**:**

	•	**What must happen for the user story to be complete?**

	•	(e.g., “The player must be able to log in with their username and password.”)

	•	(e.g., “If login fails, the player sees an error message.”)

---

**Instructions for Writing User Stories:**

For each feature you want to create, write a new user story. After each user story, include two acceptance criteria that explain how you’ll know when that story is complete.

**Do this until you have 5 user stories** in total.

Make sure each story clearly describes:

* *Who* the user is.  
* *What* the user wants to do.  
* *Why* it’s important to them.

Then, for each story, list two specific things that must happen for it to be considered "done."

---

**Examples for Simon’s Switch Up** 

**User Story 1: Player Starts the Game**  
**As a** player,  
**I want to** start the game by pressing “Begin”,  
**So that** I can choose my game mode, play and enjoy the game.  
**Acceptance Criteria:**

	•	The player should be able to see a start button at the middle of the screen.

	•	When clicked, the player should see a heading saying "What game mode are we taking on?"

	•	Below the header, two buttons should be visible saying "Casual Mode" and "Challenge Mode"

	•	Under each button, a block of text explains how the game mode is going to be like. Casual mode says "The game will go as normal and the game doesn't speed up you progress. The symbols and words still change positions so pay attention!!" while Challenge Mode says "The game will go as normal until the fifth round. It will start speeding and the penalty for getting anything wrong goes up from one and stays as it is. The symbols and words will change position so pay attention!!"

	•	When option is picked, this will start the game according to the game mode picked by the player

**User Story 2: Player picks the "Casual Moe" at the mode picking screen**  
**As a** player,  
**I want to** play the game in the casual game mode,  
**So that**  can get as far as I can with beating my high score without the a challenge added.  
**Acceptance Criteria:**

	•	The player will see a count down that will allow them to prepare to start the game. The game will take this time to get random symbols and words from the internal catalog to display once the count down is done.

	•	The player will come to a screen with "00" being displayed as their beginning score. There will be the four circle quarts displaying the options with the beginning prompt requesting the player to pick their first option to officially start gaining points.

	•	For every correct selection, they gain 5 points and for every wrong one, they lose 2 points

	•	The symbols and words (things that the prompt will ask for) will switch position

**User Story 3: Player Picks  the “Challenge Mode” at the mode picking screen**  
**As a** player,  
**I want to** Play the game in “Challenge Mode” ,  
**So that** I can get as far as I can with beating my high score with the added challenge.  
**Acceptance Criteria:**

	•	The background of the game must be distinct from casual mode so that apart from the gameplay differences, there’s a visual difference between them.	

	•	The player must be able to see a countdown as it would with Casual Mode. Once the countdown ends, the 4 circle quarts will begin to display the words & symbols and the prompt will begin. The symbols 

& words will switch positions with every round.

	•	Once the player reaches the sixth round, the game speed will slowly start to pick up in pacing every 6 rounds. The points gained will now be 6 and points lost will now be 4\.

**User Story 4: Player Hits Too Many Wrong Buttons**  
**As a** player,  
**I want to** be incentivized to not hit the limit of how wrong answers I can get in a row,  
**So that** I can enjoy the game at a baseline challenge of the game.  
**Acceptance Criteria:**

	•	The game must be able to keep log of how many mistakes can be made in a row.

	•	The game must be able to stop the game completely if this threshold is met, being 3 mistakes in a row.

	•	"Lives" are put in the corner as a visual indication of how many wrong inputs they can make and they can gain them back after the player gets 3 correct inputs in a row.

**User Story 5: Player Saves Game High Score, and or pause game play**  
**As a** player,  
**I want to** be able to pause the game when I want to, and save my score during the game and if the highscore is met and passed, I can see it in the next game.
**So that**  the new highscore is saved and then displayed
**Acceptance Criteria:**

	•	The game must allow the player to pause game play at any time to do anything they need to but there is a time frame that the app can be closed before it restarts when reoppened.

	•	When the player reaches the highscore and passes it, the game must be able to display it at the end of the game when they lose or when they reopen the app entirely to start a new game.

	•	The game must have two different highscores for both Casual and Challenge mode.

**User Story 6: Player Opens Achievements**  
**As a** player,  
**I want to** be able to open the Achievements to see what I've completed in game,  
**So that** I can keep track of what I have an haven't done according to the game.  
**Acceptance Criteria:**

	•	Player must be able to open the achievemnents and those that have been completedmust be highlighted in a different color to the one's that are yet to be completed

	•	The achievements list must update  everytime one each one is met and progress for achievements that take a lot more time compared to others should have their progress updated

	•	Player must be able to scroll through the short achievements to see all that is listed.
