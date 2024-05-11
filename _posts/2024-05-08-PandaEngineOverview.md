---
title: Panda Engine Overview
description: My Work Experience
author: Ershad
date: 2019-08-09 11:33:00 +0800
categories: []
tags: []
pin: false
math: true
mermaid: true
blog: true
image:
  path: assets/img/PandaEngine/overview.png
  lqip: 
  alt: 
---

## Description

A game engine made from scratch using OpenGL and C++. This game engine was made over a period of 8 months as part of the Game Development Advanced Programming course.

## Dependencies:
 - glfw
 - glad
 - Assimp
 - FMOD 
 - Nvidia
 - entt
 - rapidjson
 - stb_img

## Basic structure

 The game engine is built on the concepts of entity component system and is applied using the entt library.

### Initializing

Firstly, the engine needs to be initialized. This sets up all the required managers, shaders, windows, inputs etc.
 ``` c++
  Engine engine;
  if (!engine.Initialize())
  {
      return 1;
  }
 ```

### Scene

 Scene is the over-arching class that contains all the entities. The scene handles updating all the components in an entity and updates them every frame.
 Creating a scene-
 ``` c++
 Scene* scene = new Scene("sceneName");
 engine.AddScene(scene);
 ```
### GameObjects

 Gameobjects are the entities that contain components.
 Simply click on the New Game Object button in the scene UI.
 Code:
  ``` c++
GameObject* newGameObject = scene->CreateGameObject("GameObjectName:);
 ```
 All gameobjects are initialized with the transform component.

### Components

 Components are the indiviual logics of different features enlisted in the features post.
 Add a component by right clicking a gameobject and click add component.
 Code:
  ``` c++
Component* component = &newGameObject->AddComponent<Component>();
 ```

## Roadmap:


