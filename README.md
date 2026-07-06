# Autonomous-Vehicle-RL

A reinforcement learning project where autonomous vehicles learn to navigate an environment while avoiding collisions with walls.

The goal of this project is to demonstrate how reinforcement learning can control multiple autonomous agents in a real-time simulation. Every vehicle continuously evaluates its surroundings and independently decides whether to move forward, turn left, or turn right in order to maximize its reward while avoiding obstacles.

## Project Highlights

* Reinforcement Learning based autonomous vehicles
* Multi-agent simulation
* Real-time decision making
* Wall avoidance
* Independent agent behavior
* Discrete action space
* Built in Roblox for maximum accessibility

## Action Space

Each vehicle can choose one of three actions at every decision step:

* Move Forward
* Turn Left
* Turn Right

This simplified action space allows the reinforcement learning model to focus on navigation and obstacle avoidance while maintaining stable performance with many active agents.

## Why There Is No Acceleration or Braking

Acceleration, braking, and variable speed were intentionally not implemented.

The reason is not a limitation of the reinforcement learning approach itself, but the computational overhead of running many autonomous vehicles simultaneously inside the Roblox engine. Every vehicle performs continuous decision making, and increasing the action space would significantly increase the simulation cost.

The primary objective of this project is to demonstrate scalable autonomous behavior rather than realistic vehicle physics.

## Scalability

The reinforcement learning system is designed with scalability in mind.

Using a higher-performance engine or a custom simulation framework would make it possible to introduce features such as:

* Acceleration and braking
* Continuous steering
* More complex observations
* Richer reward functions
* More realistic vehicle dynamics
* Significantly larger numbers of autonomous vehicles running simultaneously

The concepts demonstrated in this project are not tied to Roblox and can be extended to more computationally demanding environments.

## Why Roblox?

Roblox was chosen because it allows anyone to experience the project instantly.

Benefits include:

* Free access
* No installation beyond Roblox
* Cross-platform support
* Easy sharing
* Large player ecosystem

This makes it an ideal platform for demonstrating reinforcement learning concepts to a broad audience without deployment costs.

## Play the Simulation

🎮 **Game:**
<[GAME_LINK](https://www.roblox.com/games/136079968969937/Ai-Car)>

## Watch the Demo

🎥 **Video:**
<[VIDEO_LINK](https://youtu.be/P98LSWvFeik)>

## Technologies

* Reinforcement Learning
* Luau (Roblox)
* Roblox Studio
* Multi-Agent AI
* Autonomous Navigation

## Future Work

Potential improvements include:

* Continuous action space
* Dynamic vehicle speed
* Traffic rules
* Lane following
* Traffic lights
* Better reward engineering
* Larger environments
* Higher agent counts using a more performant engine

## License

This project is released for educational and demonstration purposes.
