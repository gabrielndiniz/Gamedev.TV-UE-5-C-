\# UE5 C++ Study – Obstacle Assault



This repository documents my study of Unreal Engine 5 with C++, following the course:



\*\*Unreal Engine 5 C++ Developer: Learn C++ \& Make Video Games\*\*

by GameDev.tv

Section: Obstacle Assault



The goal of this project is to build a strong foundation in C++ applied to Unreal Engine 5 by developing a small gameplay prototype focused on moving platforms, obstacles, and core engine architecture.



---



\## Objectives



\* Set up a proper Unreal Engine 5 C++ development environment

\* Understand how C++ integrates with Unreal Engine

\* Learn the Actor lifecycle (BeginPlay, Tick)

\* Work with UPROPERTY, UFUNCTION, and Unreal macros

\* Implement movement logic using FVector and delta time

\* Create reusable gameplay components (e.g., moving platforms)

\* Combine C++ systems with Blueprints

\* Document key learnings and implementation decisions



---



\## Technologies



\* Unreal Engine 5

\* C++

\* Visual Studio (Windows) or Xcode (Mac)

\* Unreal Build Tool



---



\## Core Concepts Covered



\### Project Setup



\* Creating a C++ Unreal project

\* Understanding project structure (Source, Content, Build files)



\### Unreal C++ Fundamentals



\* AActor classes

\* Components

\* UPROPERTY and editor exposure

\* Header and source file structure

\* Unreal reflection system basics



\### Gameplay Flow



\* BeginPlay()

\* Tick(float DeltaTime)

\* Frame-independent movement

\* FVector math



\### Moving Platform System



\* Configurable movement distance

\* Speed control

\* Direction switching

\* Editor-exposed variables



\### C++ and Blueprint Integration



\* Exposing properties to the editor

\* Using C++ logic inside Blueprint actors

\* Extending C++ classes via Blueprint



---



\## Example Project Structure



```

ObstacleAssault/

├── Source/

│   ├── ObstacleAssault/

│   │   ├── ObstacleAssault.cpp

│   │   ├── ObstacleAssault.h

│   │   ├── MovingPlatform.cpp

│   │   ├── MovingPlatform.h

│   │   └── ...

├── Content/

│   ├── Maps/

│   ├── Blueprints/

│   └── Assets/

├── Config/

└── ObstacleAssault.uproject

```



---



\## How to Run



1\. Clone the repository.

2\. Open the `.uproject` file with Unreal Engine 5.

3\. Allow Unreal to generate project files if prompted.

4\. Compile using Live Coding or your IDE.

5\. Open the main level and press Play.



---



\## Key Learning Outcomes



\* Understanding Unreal's gameplay framework

\* Writing clean, modular C++ gameplay code

\* Debugging inside Unreal Engine

\* Managing editor-exposed parameters safely

\* Building reusable gameplay systems



---



\## Notes



This project is focused on learning and experimentation. Code may evolve as understanding of Unreal Engine architecture improves.



The emphasis is on clarity, structure, and solid C++ fundamentals applied to real-time gameplay systems.



