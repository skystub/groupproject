# groupproject
## Hacker game
Overview: one player is the hacker infiltrating a facility, while the other players are security agents trying to stop them. The hacker has to navigate through a map, reach three data terminals and collect data, and then reach an escape point to win. To collect data and escape there are minigames the hacker has to complete.

The hacker sees the map from a top-down perspective while the agents move in first person view. The agents use traps, surveillance and communication to track the intruder down. The agents can also hear (or see) the hacker's avatar and which direction the noise is coming from, but also each other and occasionally just noises in the map.  The hacker has limited time and energy. They have the ability to change things on the map to avoid the agents, but if they do too much too fast they could overload the network and cause a lockdown, which makes it very hard to escape. 
 
## Target Audience:
Age Group: 13+
Interests: asymmetric multiplayer games, hacking/technology themes, real time strategy

## Main Features
### Roles
Hacker: top down view, wins by hacking 3 terminals + escaping
Agents: 1st person view, win by catching the hacker or stalling them until they run out of time. 

### Tools/Abilities
Hacker: 
Temporary invisibility
Camera hijack: disables security camera for ten seconds
Door override: locks or unlocks a nearby door
Noise: decoy sound at selected location
Virus: slows agent tracking tools
Overclock: speeds up terminal minigame (at a lot of expense)

Agents:
Scanner: reveals general direction of movement in a radius around the agent
Map: can see data terminals and which ones have been taken. When hacker has done a lot of hacking/used a lot of tools, hacker is pinged on agent map
Trip mine: stuns hacker for a certain amount of time if triggered
Lock: temporarily seals a room of choice
Motion sensor: alerts when someone passes through a door
Firewall: one time use in late gameplay to restrict hacker tools (when hacker has reached full network load)
Taser: if encounters hackers avatar, captures them

## User Flow
Pick map & time limit difficulty
Decide who is agent/hacker or can randomize with a button

### Hacker flow
Choose a terminal to approach on map, control avatar to reach terminal without being caught by agents
Complete minigame
Avoid agents while going to next terminal
After hacking 3 terminals, find the escape point

### Agent flow
Patrol map
Respond to alerts
Place traps
Track down the hacker and try to stop them

## Visual notes
Hacker UI elements: trace meter, network load bar, tools with cooldown timers, top down map view
Agent UI elements: tools with cooldown timers, inside map without top down view 
