- dashboard

- [ ] create opening page, mode selection, options...
- [ ] create opening dashboard
- [ ] dashboard index -> react-router
- [ ] add some kind of bundler

- client

  - [ ] add react-router

  - [ ] create an entry point function for the client code which creates a canvas, and starts the game loop
  - [ ] a user shall be able to move their player around with w,s,a,d
  - [ ] a user shall be able to move in a diagonal direction
  - [ ] a user shall be able to attack using space
  - [ ] a user shall be able to see a mini map which helps them know where they are
  - [ ] a user shall be able to see a health bar which shows how much health they have
  - [ ] a user shall be able to run using shift
  - [ ] a user shall be able to see stamina bar which recharges slowly over time

  - [ ] start the "day" cycle which allows 5 minutes for players to build, explore, and gather resources
  - [ ] start the "night" cycle which spawns waves of zombies for 5 minutes which the players need to survive
  - [ ] a user can cut down trees which drops wood
  - [ ] a user can pick up wood which puts it in their inventory
  - [ ] a user can build a barricade with wood which have 10 hp and forces the zombies to attack the barricade before they can get to the players. The barricade does not block path finding, meaning zombies will intentially try to run into them if it's the best path between them and the player.
  - [ ] a user can move up, down, left, and right
  - [ ] a user can fire in the direction they are facing
  - [ ] a user should be able to destroy barricades (if they are stuck, hold X for 3 seconds)
  - [ ] a user can drop items from their inventory
  - [ ] a user can hold one weapon at a time
  - [ ] a user spawns with a baseball bat (melee weapon, slow attack speed, has knock back)
  - [ ] a user can search a dead zombie body for items (randomly drop items)
  - [ ] a user can search cabinets for items (randomly drop items)
  - [ ] a zombie can attack a player (when they get close enough to a player, we need an attack animation and only hurt the player if they close enough by the time the animation reaches a certain point)

- server

- multiplayer features(maybe)
