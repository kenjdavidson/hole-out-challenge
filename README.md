# Hole Out Challenge

Playing around with Unity using my love of golf as a gateway.   Will attempt to document the process:
 
## Goal: Project Setup

The goal of these topics is to get a basic functional driving range.

### Project Creation and Unity Setup

## Goal: Stimp Meter Scene

Provide a scene which shows a **Green** area and a **Stimp Meter**.  The user will be able to:

- [ ] Pick which stimp they which to apply to the green
- [ ] Configure the simulation, number of golf balls, etc
- [ ] Reset the scene

## Goal: Basic driving Range

Provide a scene which allows the launch of golf balls while controlling a number of the user launch conditions.   Golf balls should:

- [ ] Fly at appropriate trajectories
- [ ] Handle all 4 wind directions
- [ ] Correctly handle interactions with differnet ground types
- [ ] Implement some UI for providing launch settings, or
- [ ] Implement some kind of launch monitor

### Implement SLX Communication

In order to perform testing and make this worth while, I'd like to be able to use the game with my SLX Micro launch monitor.  This will require:

- [ ] Design an interaction model to use with launch monitors
- [ ] Create the SLX Connect implementation
- [ ] Create UI elements to allow for configuration and display of connections status

## Goal: Create some mini games

The goal of this will be learning to build different scene managers, game managers, etc.

- [ ] A memory card game where each player can hit different shots to flip different cards
- [ ] Tic tac toe for Golf shots, both horizontal (ground) and vertical (shot shape)

## Goal: Procedural Generation of Driving Range

- [ ] Procedurally generate the driving range, include all types of ground
- [ ] Procedurally generate the environment (Wind, Air, etc)
