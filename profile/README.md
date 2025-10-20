## Hello !
Welcome to Rye's comprehensive software portfolio! It's a lot, and there's more under the surface.

## Coursework from North Carolina State University
Samples of classwork are private but available upon request.

* *Software Engineering.* (CSC326)
  * Drafted requirements for, implemented, and tested a mobile order pickup site
  * Collaboration between a 6-person team on GitHub using Issues, Pull Requests, Projects, and Wikis
  * Test-driven development constituting 90% line coverage and 70% method coverage
  * Backend: Java on Spring Boot + Maven with Lombok library and Jakarta ORM
  * Frontend: Javascript on React + Vite

* *Data Structures & Algorithms.* (CSC316)
  * Demonstrated knowledge of Javadoc and unit, integration, and system testing with command-line programs
  * Benchmarked performance of 2 networking algorithms and charted their performance in terms of `O(g(n))`

* *Computer Organization & Assembly Language.* (CSC236)
  * Demonstrated knowledge of low-level concepts like CPU caching, linkage, and addressing/allocating to stack/heap
  * Compiled 8086 assembly code for MS-DOS for 9 algorithms including maze-solving, Salamin-Brent, and decompression

* *C & Software Tools.* (CSC230)
  * Practiced safe handling of input, pointers, strings, buffers, and overflowing arithmetic
  * Implemented command-line programs with quality-assurance unit testing and code coverage reports

* *Intro to Robot Motion Planning.* (CSC495-RMP)
  * Coded in Python on ROS2 with [FCL](https://pypi.org/project/python-fcl/) library and RViz visualizer
  * Implemented and tested inverse kinematics, trajectory generation, GJK collision detection, and RRT pathfinding

* *Intro to Responsible Machine Learning.* (CSC495-RML)
  * Experimented in Python on Colab with PyTorch library
  * Discussed attributes of ML trustworthiness and safety, the ML lifecycle, data sourcing and ethics, and algorithmic bias

## Collaborative projects
* *tModLoader port to .NET Core and FNA.* ([repo](https://github.com/tModLoader/tModLoader/pull/1086))
  * Collaborated with four primary developers of tModLoader (#50 for daily users on Steam with over 60 million downloads)
  * Ported tModLoader from .NET Framework XNA to .NET Core 3.1 FNA over 8 months
  * Improved portability and let modders use modern C# language features and .NET Core libraries
 
* *Rain World custom game object library.* (TODO repo)
  * Addressed gap in mod compatibility with a FOSS code library to define custom game objects and creatures
  * Maintained over multiple breaking-change updates with help from community contributions; now community standard
 
* *Rain World input configuration library.* (TODO repo)
  * Addressed inability for plugin creators to create custom, configurable controls
  * Designed and implemented a FOSS dependency that beautifies and standardizes game input, now used by multiple mods
  * Maintained solely by community contributions and forks

## Independent projects
* *Sample ASP.NET Core project.* ([repo](https://github.com/rye-pf/prometheus-assessment))
  * C# 12 on .NET 8 with ASP.NET Core library
  * Consumes a stock API, performs basic data analysis on the response, and exposes data as new REST API

* *Rain World plugin loader.* (TODO repo)
  * Developed and maintained mod loader client, daemon, server, and database. Semver and REST compliant
  * Client: Interfaces with user directly. Unity C# with Futile framework on .NET Framework 3.5
  * Daemon: Uploads, downloads, and patches plugins; Auto-updates. C# on .NET 5
  * Server: Exposes API to list, get, and post plugins; Auto-uploads from GitHub releases. Rust with Rocket framework
  * Hosted *for free* with 98% uptime using railway.com and MongoDB

* *Rain World multiplayer injection.* (TODO repo)
  * Explored lag compensation and server-client authority (client-side physics interpolation with server validation)
  * Injected game with BepInEx to make it into a headless terminal or daemon capable of serving multiple clients

* *Rain World quality-of-life plugins.* (multiple repos)
  * Addressed multiple game features that needed polishing
  * Created game rules, dev console, object persistence, and accessibility controls/features

* *.NET assembly parser and patcher.* (TODO [repo](https://github.com/Dual-Iron/oxil/tree/read), 'read' breach)
  * Implementing an idiomatic Rust library to inspect and modify .NET assemblies from official Microsoft spec
  * Designed bottom-up to be performant, thread-safe, memory-safe, and foolproof with extensive documentation
  * Run entirely on the stack

<!--
projects https://docs.google.com/document/d/1cPU6ozPMYfJz1ZZkQZQCYjD_Wg_1h71oSBGFBj_vXCY/edit?tab=t.0
RML https://drive.google.com/drive/folders/1hyRtcdDmmC9WBEOIVyvu5RqJDz3Hfj22

describe tech used for each
-->
