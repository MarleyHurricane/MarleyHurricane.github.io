---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Creating a Battleships-like War Game"
date: 2024
published: false
labels:
  - WWII
  - Strategy Game
summary: "A 3D Battleships-like game where two or more players fight with their ships, submarines and aircrafts in a turn-based game."
---

# The Game

## The Game Board

## The Pieces
### Sea
|Name|HP|Abilities|
|---|---|---|
|Aircraft Carrier|500|Generate 1 plane every 5 turns. Can prevent an airstrike every 3 turns. Can store 5 planes per carrier|
|Nuclear Submarine|300|Can launch a nuclear missile every 5 turns. Has a blast radius of 7. Damage can be interpolated between 700 HP 0 units away, to 100 HP 7 units away. Can dive below water (Preventing all attacks except for depth charges). Diving prevents the launch of nuclear missiles, and takes 3 turns. Diving prevents radardetection|
|Battleship|400|Has a heavy main cannon. This can deal 200HP damage to enemy pieces within 5 units. It can repair 50HP if it does not deal any damage in a turn.|
|Destroyer|300|Has a light main cannon. This can deal 100HP damage to enemy pieces within 4 units. They can launch depth charges, which deal 200HP from submarines, up to 5 units away.|
|Frigate|200|Has a super-light cannon. This can deal 50HP to pieces within 3 units. They can launch depth charges, which deal 200HP from submarines, up to 5 units away.|
|Patrol Boat|50|Enemy pieces within 3 units of the patrol boat are revealed. Patrol Boats can see Submarines which have dived, if they are within 3 units|

### Air

|Name|HP|Abilities|
|---|---|---|
|Fighter|200|Deal 150HP to enemy pieces within 4 units.|
|Bomber|400|Deal 400HP to enemy pieces within 4 units of bomb landing location, up to once every 2 turns.|
|Recon Plane|50|Reveals enemy pieces within 5 units. Does not reveal Submarines which have dived.|

### Land
|Name|HP|Abilities|
|---|---|---|
|Tanks|300|Deal 200HP to enemy pieces within 3 units.|
|Artillery|200|Deal 100HP to enemy pieces within 5 units.|

infantry
infantry trucks
anti-tank guns
machine gun jeeps
