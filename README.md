# Clash of Class
A strategy game based on the Clash of Clans online game

**CMSC 137 Project Proposal**
**Team RGB**

Genio, Rafhael  
Sy, Gerald  
Doron, Michael Bernard Bryan  

**Game Name:** Clash of Class  
**Description:** A strategy game based on the popular mobile game Clash of Clans  

##Game Elements
1. Structures
  1. Crystal Tower
  
    Instead of building structures like the usual CoC gameplay, only one strucutr will be appearing during gameplay: The crystal tower. This tower serves as a lifeline of every player. If this tower collapses, the player will immediately lose the game. There will be three types of towers depending on its defense capability. A thick-walled tower (structural defense), a tower with heavy artillery (aerial defense), and a tower with land mines (ground defense).
  2. Training Ground
  
    A player has a maximum of 240 troops that can be deployed. However, the player has a maximum to choose the characters that will be spawned during battle using the training ground. Inside the ground, the player can deploy at most 12 troop huts. Each character has its own troop hut (and the number of troops inside a troop hut depends on the troop type), and the player can only build a limited number of a character’s troop hut depending on its strentgth and capability
2. Characters

	There will be 5 characters in the game (Stats might change on Development Process):
	
  1. NF  
      **Characteristics:** Quick attacker and mover, but has a very low HP. Attack power is not powerful enough. Best if clustered in a group   
	    **Attack Power:** 50    
	    **Defense:** 50    
	    **Speed:** 60    
	    **Number of Troops per Hut:** 20    
	    **Max number of Troop huts that can be deployed:** 6    
  2. OF  
    **Characteristics:** Almost the same as NF, but attack power increased slightly in exchange to a much slower speed.  
		**Attack Power:** 60  
		**Defense:** 50  
		**Speed:** 60  
		**Number of Troops per Hut:** 20  
		**Max number of Troop huts that can be deployed:** 6  
  3. Sophomore  
    **Characteristics:** Attack power in average, heavy defense capability. Speed is very low. Best in defending bases as a shield or barrier.  
		**Attack Power:** 65  
		**Defense:** 75  
		**Speed:** 50  
		**Number of Troops per Hut:** 10  
		**Max number of Troop huts that can be deployed:** 4
  4. Junior  
    **Characteristics:** Attacks accurately and has a very high hit ratio. Moves fast to infiltrate other bases but has a low defense mechanism.  
		**Attack Power:** 50  
		**Defense:** 60  
		**Speed:** 75  
		**Number of Troops per Hut:** 10  
		**Max number of Troop huts that can be deployed:** 4
  5. Senior  
    **Characteristics:** Very powerful long range attack that hits a larger ratio of enemies. Very hard to control as it moves slower. Defense is also powerful  
		**Attack Power:** 80  
		**Defense:** 75  
		**Speed:** 40  
		**Number of Troops per Hut:** 2  
		**Max number of Troop huts that can be deployed:** 2  
3. Power-ups  
  Before starting a battle the playercan opt to use one power-up to boost the gameplay:  
  1. The Pride of Arabia  
    Junior troops will explode and kill troops near it if 	an enemy troop kills it. Can break walls of the crystal tower too if exploded near it  
  2. The Hovertroop  
    Sophomore troops can move past landmines near the Crystal Tower if the crystal tower is equipped with one
  3. The Katniss effect  
    Sophomore troops get an archer capability that can destroy artillery of a crystal tower  
4.  Game Mechanics
	1.  Starting the Game  
      1. The player will be welcomed to a world menu where he/she can see all players that are online. In that menu he/she can check his rankings based on the Tower Fallen points (TF), check settings and engage other users to a battle.  
      2. In starting a battle the player must select three online users and those three other users must accept the invitation before engaging to a battle.  
      3. Once all three users are engaged, the game will start.  
	2.  Playing the Game  
      1. Before engaging to battle each user will start with the training ground. The player must choose what troop huts will he choose for the battle. The user cannot go back to the training ground once battle has commenced
      2. If all users are ready for the battle, the battle screen will appear which is basically a map with three bases (bases of the users) and on the bottom of the screen will be the list of all troops selected from the training ground and the number of troops left to deploy on the ground. 
      3. The game will be timed for 5 minutes maximum.
      4. You can deploy a troop on the ground by clicking on the map where you want the troop to be deployed. Once the troop is deployed, the player cannot un-deploy or move the troop from one place to another. The troop will move itself to the nearest base it is deployed and will either protect the crystal tower(if it is the player’s base) or attack it (if it’s an enemy base).
      5. Once a troop is on the ground, it will do an action based on its current situation (if attacked, near the base of the enemy or defending it). 
      6. If a power-up is selected, it will be available as an option near the troops. To activate it, click the power-up. It will be active for a limited number of time only and can be re-used after the cool-down period. Every power-up has a different cool down period
      7. A troop can die in game, and the player can monitor the number of his troops on the counter on the top of the screen.
	3. Winning the game  
      1.  There can only be one winner per game and will be determined by the following metrics:
        1. If the player’s troops are the last men standing (or alive) in the game
        2. If all but a player’s crystal tower is destroyed (Only one crystal tower remains)
        3. If the time of the game ends, the winner will be calculated on the player whose crystal tower with the less damage (based on the tower’s health points).
      2. If the player’s crystal tower falls and if the player’s troops are all dead, the player automatically loses the battle.
      3.  The winner will get two additional Tower Fallen (TF) points after the battle.
