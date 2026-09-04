# TERREX

## World-Aware 3D Reconstruction Platform

> From geographic data and real-world observations to persistent, explorable 3D environments.

TERREX is a full-stack platform for representing real-world locations as interactive 3D environments.

The platform combines geographic information, persistent world memory, real-world observations, 3D reconstruction, terrain generation, real-time multiplayer and environmental simulation into a single explorable world.

---

## 🌍 Explore TERREX

**Live World:** Coming soon

TERREX is designed to allow users to explore reconstructed real-world environments through an interactive 3D interface.

The live world will provide access to geographic entities, terrain, buildings, 3D assets, environmental systems and multiplayer interactions.

---

## Overview

TERREX explores a different approach to representing real-world environments.

Instead of treating a 3D model as an isolated asset, TERREX associates reconstructed objects with geographic entities, observations and persistent world state.

A simplified representation of the system is:

```text
                         REAL WORLD
                             │
               ┌─────────────┴─────────────┐
               │                           │
        Geographic Data              Photographs
               │                           │
               └─────────────┬─────────────┘
                             ▼
                       OBSERVATIONS
                             │
                             ▼
                       WORLD MEMORY
                             │
                       Entity Matching
                             │
                             ▼
                      RECONSTRUCTION
                             │
                             ▼
                         3D ASSET
                             │
                             ▼
                       TERREX WORLD
