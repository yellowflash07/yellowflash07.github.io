---
title: Yet Another Zombie Shooter
description: My Work Experience
author: Ershad
date: 2019-08-08 11:33:00 +0800
categories: []
tags: []
pin: false
math: true
mermaid: true
blog: true
image:
  path: assets/img/PandaEngine/poster.png
  lqip:
  alt: 
---

## Description

Final project made for GDP 2023-24. This project employs all the techniques learnt during the course and various techniques learnt outside of the course work.

## Project Features

1. [Shadows](#shadows)
2. [Normal maps](#normal-maps)
3. [PhysX](#physx)
4. [Vehicle](#vehicle)
5. [Async Loading](#async-loading)
6. [Dynamic LOD](#dynamic-lod)
7. [Animation Blending](#animation-blending)
8. [Bone Attachment](#bone-attachment)

## Shadows

![alt-text](assets/img/PandaEngine/shadow.png)

## Normal maps

Using normal maps to create realistic lightings and making bumps on the meshes.

![alt-text](assets/img/PandaEngine/normal.png)

## PhysX

### Character Controller

Using a capsule collider that climb slopes and automatically step on certain heights! Thanks to Nvidia PhysX's character controller component.

![Alt Text](assets/img/PandaEngine/character-controller.gif)

### Raycast

Shooting using raycast!

![Alt Text](assets/img/PandaEngine/raycast.gif)

## Vehicle

Vroom! Full vehicle physics including engines, wheels, wheel friction, drifting, realistic acceleration, deceleration.

![Alt Text](assets/img/PandaEngine/vehicle.gif)

## Async Loading

All the meshes are loaded on thread. This speeds up the load time.

## Dynamic LOD

Triangle generation on the fly! Using tessellation shaders.

![Alt Text](assets/img/PandaEngine/dynamicLOD.gif)

## Animation Blending

Blending animations between different states.

![Alt Text](assets/img/PandaEngine/animation-blend.gif)

## Bone Attachment

Gun attached to hand.

