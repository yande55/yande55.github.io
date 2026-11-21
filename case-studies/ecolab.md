# EcoLab: keeping the simulation separate from the game engine

Real-time educational simulation tool (Unity, GAM300 capstone).

**What I owned:** the simulation logic.

**The problem:** the simulation needed to be testable and reusable, but if it lived inside the Unity game, it could only run inside Unity.

**My choice:** I built the simulation as a standalone C++20/23 module, kept separate from the Unity UI layer.

**The result:** the simulation can be tested and reused outside the game engine.
