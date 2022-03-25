- [Introduction to AR, VR & Game Development](#introduction-to-ar-vr--game-development)
  - [Building Games](#building-games)
    - [Setting up gameobject](#setting-up-gameobject)
    - [Adding Hero, obstacle and goal](#adding-hero-obstacle-and-goal)
    - [Adding moving enemies](#adding-moving-enemies)
    - [Adding platforms](#adding-platforms)
    - [Designing levels](#designing-levels)
    - [Controlling player with mouse](#controlling-player-with-mouse)
    - [Adding shooter gameobject](#adding-shooter-gameobject)
    - [Adding shooting mechanics for the player](#adding-shooting-mechanics-for-the-player)
    - [Having score computing system](#having-score-computing-system)
    - [Adding background and scrolling effect](#adding-background-and-scrolling-effect)
    - [Creating winning screen](#creating-winning-screen)
    - [Making it Multiplayer](#making-it-multiplayer)
    - [Computing and showing the score for both the players](#computing-and-showing-the-score-for-both-the-players)
  - [AR with Spark AR Studio](#ar-with-spark-ar-studio)
    - [Creating lters and masks](#creating-lters-and-masks)
    - [Adding effects like VHS, dust, scratches](#adding-effects-like-vhs-dust-scratches)
    - [Creating an immersive particle effect](#creating-an-immersive-particle-effect)
    - [Working with textures and materials](#working-with-textures-and-materials)
    - [Animating 3D objects in real world](#animating-3d-objects-in-real-world)
    - [Face Tracking Effect and Iris Tracking](#face-tracking-effect-and-iris-tracking)
    - [Responding to Facial Movement](#responding-to-facial-movement)
    - [Face Gestures](#face-gestures)
  - [Create apps for WebVR with A-Frame](#create-apps-for-webvr-with-a-frame)
    - [Going through A-Frame examples](#going-through-a-frame-examples)
    - [Start with scene and transform the objects](#start-with-scene-and-transform-the-objects)
    - [Importing and displaying 3D models](#importing-and-displaying-3d-models)
    - [Adding Textures](#adding-textures)
    - [Using animations](#using-animations)
    - [Interaction with the objects](#interaction-with-the-objects)
    - [Teleportation](#teleportation)
    - [Using and modifying the controls](#using-and-modifying-the-controls)
    - [Playing video and audio](#playing-video-and-audio)
    - [Controlling entities with Javascript](#controlling-entities-with-javascript)
    - [Testing WebVR scenes](#testing-webvr-scenes)
- [C# Scripting Fundamentals in Unity](#c-scripting-fundamentals-in-unity)
  - [Basics of C](#basics-of-c)
    - [Data types, Variables and Constants](#data-types-variables-and-constants)
    - [Conventions and Syntax](#conventions-and-syntax)
    - [Conditional Statements & Operators](#conditional-statements--operators)
      - [If, else](#if-else)
      - [Switch Statements](#switch-statements)
      - [Ternary Operator](#ternary-operator)
    - [Loops](#loops)
    - [Arrays, Lists and Dictionaries](#arrays-lists-and-dictionaries)
    - [Functions](#functions)
    - [Scope and Access Modi ers](#scope-and-access-modi-ers)
  - [Classes and Namespaces](#classes-and-namespaces)
    - [Static Class](#static-class)
    - [Partial Class](#partial-class)
    - [Nested Class](#nested-class)
    - [Inheritance](#inheritance)
  - [About MonoBehaviour](#about-monobehaviour)
    - [Awake and Start](#awake-and-start)
    - [Update and FixedUpdate](#update-and-fixedupdate)
    - [Enabling and Disabling Components](#enabling-and-disabling-components)
    - [Destroy](#destroy)
  - [Gameobject and Transform](#gameobject-and-transform)
    - [Activating GameObject](#activating-gameobject)
    - [Translate and Rotate](#translate-and-rotate)
    - [GetComponent](#getcomponent)
    - [Instantiate](#instantiate)
  - [Reading Inputs](#reading-inputs)
    - [GetButton and GetKey](#getbutton-and-getkey)
    - [GetAxis](#getaxis)
    - [Mouse and Pointer Functionalities](#mouse-and-pointer-functionalities)
  - [Vector Maths](#vector-maths)
    - [Vector Arithmetic](#vector-arithmetic)
    - [Dot and Cross Products](#dot-and-cross-products)
    - [Computing Normal vector](#computing-normal-vector)
    - [Projecting one vector onto the other](#projecting-one-vector-onto-the-other)
  - [Adding Movement](#adding-movement)
    - [Linear Interpolation](#linear-interpolation)
    - [DeltaTime](#deltatime)
    - [Invoke](#invoke)
    - [Enumerations](#enumerations)
    - [Quaternions](#quaternions)
- [Advanced C# Scripting](#advanced-c-scripting)
  - [More about Classes and Methods](#more-about-classes-and-methods)
    - [Creating Properties](#creating-properties)
    - [Method Overloading](#method-overloading)
    - [Overriding](#overriding)
    - [Interfaces](#interfaces)
    - [Extension Methods](#extension-methods)
    - [Coroutines](#coroutines)
    - [Abstract Classes](#abstract-classes)
    - [Delegates and Events](#delegates-and-events)
    - [Statics](#statics)
    - [Generics](#generics)
    - [Member Hiding](#member-hiding)
    - [Object Pools](#object-pools)
    - [Attributes](#attributes)
    - [LINQ](#linq)
    - [Lambda Expressions](#lambda-expressions)
    - [Asynchronous Programming with Async / Await](#asynchronous-programming-with-async--await)
  - [Data Structures](#data-structures)
    - [Linked Lists](#linked-lists)
    - [Stacks, Queues](#stacks-queues)
    - [Trees](#trees)
  - [Design Patterns for App Developers](#design-patterns-for-app-developers)
    - [Singleton](#singleton)
    - [Game Loop and Update Method](#game-loop-and-update-method)
    - [Observer, Mediator, Template](#observer-mediator-template)
  - [Selected topics in C](#selected-topics-in-c)
    - [Exception handling](#exception-handling)
    - [Text Files Streaming Assets](#text-files-streaming-assets)
    - [Playerprefs](#playerprefs)
    - [Editor Scripting](#editor-scripting)
    - [Scriptable Objects](#scriptable-objects)
    - [C# Job System](#c-job-system)
    - [Entity Component System](#entity-component-system)
- [Fundamentals of 3D Application Development](#fundamentals-of-3d-application-development)
  - [Working in 3D Space](#working-in-3d-space)
    - [Unity Editor Basics](#unity-editor-basics)
      - [Creating a 3D unity project](#creating-a-3d-unity-project)
      - [Walkaround of Unity Windows](#walkaround-of-unity-windows)
      - [Using Tools](#using-tools)
    - [Gameobjects and Assets](#gameobjects-and-assets)
      - [Creating and Positioning gameobjects](#creating-and-positioning-gameobjects)
      - [Importing Assets into a Project](#importing-assets-into-a-project)
    - [Prefabs](#prefabs)
      - [Con gure Prefabs for use throughout a scene](#con-gure-prefabs-for-use-throughout-a-scene)
      - [Nested Prefabs Prefab Variants](#nested-prefabs-prefab-variants)
  - [Setting Up the Scene](#setting-up-the-scene)
    - [Camera Setup](#camera-setup)
    - [About Skybox](#about-skybox)
    - [Adjusting Lighting](#adjusting-lighting)
      - [Light Sources](#light-sources)
  - [Preparing Assets for Implementation](#preparing-assets-for-implementation)
    - [Creating and Using Materials](#creating-and-using-materials)
    - [Importing and Using Textures](#importing-and-using-textures)
      - [Types of Shaders](#types-of-shaders)
      - [Texture size best practices](#texture-size-best-practices)
    - [Adding Textures](#adding-textures-1)
    - [Meshes and Mesh Renderers](#meshes-and-mesh-renderers)
  - [Play Music In Your App](#play-music-in-your-app)
    - [Audio Listener](#audio-listener)
    - [Audio Source](#audio-source)
  - [Customizing the UI](#customizing-the-ui)
    - [Unity UI Components](#unity-ui-components)
      - [Canvas and Panel](#canvas-and-panel)
      - [Button and Toggle](#button-and-toggle)
      - [Sprites and Image](#sprites-and-image)
      - [TextMesh Pro and Input Field](#textmesh-pro-and-input-field)
      - [Slider and Scroll View](#slider-and-scroll-view)
    - [Design UI for Multiple Resolutions](#design-ui-for-multiple-resolutions)
      - [Layouts](#layouts)
      - [Content Size Fitters](#content-size-fitters)
  - [Learn Unity’s Physics System](#learn-unitys-physics-system)
    - [Rigidbody](#rigidbody)
    - [Understanding Collisions](#understanding-collisions)
    - [Colliders and Triggers](#colliders-and-triggers)
    - [Velocity, Force](#velocity-force)
    - [Torque](#torque)
    - [Raycast](#raycast)
  - [Controlling Animation](#controlling-animation)
    - [Animator Setup](#animator-setup)
      - [Controller](#controller)
      - [State Machine](#state-machine)
      - [Scripting](#scripting)
    - [Animation Clips](#animation-clips)
  - [Navigation and Pathfinding](#navigation-and-pathfinding)
    - [Navigation System in Unity](#navigation-system-in-unity)
    - [Navmesh Agents](#navmesh-agents)
    - [Building and Baking Navmesh](#building-and-baking-navmesh)
  - [Building to devices](#building-to-devices)
    - [Build Settings](#build-settings)
    - [Project Settings](#project-settings)
      - [Audio](#audio)
      - [Editor](#editor)
      - [Graphics](#graphics)
      - [Physics](#physics)
      - [Quality](#quality)
      - [Time](#time)
    - [Different platforms](#different-platforms)
      - [Android, iOS](#android-ios)
      - [Windows, Mac, Linux](#windows-mac-linux)
- [Mastering 3D Application Development](#mastering-3d-application-development)
  - [CamerasandE ects](#camerasande-ects)
    - [Field of View](#field-of-view)
    - [Occlusion Culling](#occlusion-culling)
    - [Adding Effects](#adding-effects)
      - [Particle Systems](#particle-systems)
      - [Writing Custom Shaders](#writing-custom-shaders)
      - [Post Processing](#post-processing)
      - [Render Pipelines](#render-pipelines)
    - [More about Lighting](#more-about-lighting)
      - [Shadows](#shadows)
      - [LightMapping](#lightmapping)
      - [Reflection and Light Probes](#reflection-and-light-probes)
      - [Realtime Global Illumination](#realtime-global-illumination)
    - [Using More than one Camera](#using-more-than-one-camera)
    - [Visual Effects Components](#visual-effects-components)
      - [Lens Flare](#lens-flare)
      - [Line Renderer](#line-renderer)
      - [Trail Renderer](#trail-renderer)
      - [Billboard Renderer](#billboard-renderer)
      - [Projector](#projector)
    - [About ColorSpace](#about-colorspace)
      - [Linear](#linear)
      - [Gamma work ow and Textures](#gamma-work-ow-and-textures)
  - [Advanced Audio](#advanced-audio)
    - [Audio Mixer](#audio-mixer)
    - [Audio Spatializer](#audio-spatializer)
    - [Audio Filters](#audio-filters)
    - [Ambisonic Audio](#ambisonic-audio)
  - [Importing settings](#importing-settings)
    - [Importing Animations](#importing-animations)
    - [Importing Models](#importing-models)
  - [Advanced Physics System](#advanced-physics-system)
    - [Joints](#joints)
    - [Physics Material](#physics-material)
    - [Character Controllers](#character-controllers)
    - [Multi-scene Physics](#multi-scene-physics)
  - [Adding Constraints](#adding-constraints)
    - [Using Parent](#using-parent)
    - [About LookAt, Aim etc](#about-lookat-aim-etc)
  - [Creating Environments](#creating-environments)
    - [Creating and editing Terrains](#creating-and-editing-terrains)
    - [Trees and Tree Editor](#trees-and-tree-editor)
  - [Adding 3D art and Animations](#adding-3d-art-and-animations)
    - [Editing Animation Clips - Adding events and curves](#editing-animation-clips---adding-events-and-curves)
    - [Humanoid and Non Humanoid Animations](#humanoid-and-non-humanoid-animations)
    - [Avatar](#avatar)
    - [Rig](#rig)
    - [Animator Controller Layer](#animator-controller-layer)
    - [Avatar Mask](#avatar-mask)
    - [Blend Trees](#blend-trees)
    - [Inverse Kinematics](#inverse-kinematics)
  - [Using Navmesh and PathFinding](#using-navmesh-and-pathfinding)
    - [Off-Mesh links](#off-mesh-links)
    - [Obstacles](#obstacles)
    - [Navmesh Area](#navmesh-area)
    - [Coupling Animation and Navigation](#coupling-animation-and-navigation)
  - [Multiplayer Games and Apps](#multiplayer-games-and-apps)
    - [Multiplayer Overview](#multiplayer-overview)
    - [Setting up a multiplayer project](#setting-up-a-multiplayer-project)
    - [Using the Network Manager](#using-the-network-manager)
    - [Multiplayer APIs](#multiplayer-apis)
  - [Powering Cameras with Cinemachine](#powering-cameras-with-cinemachine)
    - [Using Virtual Cameras](#using-virtual-cameras)
    - [Cinemachine Brain](#cinemachine-brain)
    - [2D graphics](#2d-graphics)
    - [Cinemachine Impulse](#cinemachine-impulse)
  - [Create Cinematic content using Timeline](#create-cinematic-content-using-timeline)
    - [Using the Timeline window to record basic animation](#using-the-timeline-window-to-record-basic-animation)
    - [Timeline Preview and Timeline Selector](#timeline-preview-and-timeline-selector)
    - [Timeline Inspector](#timeline-inspector)
      - [Setting Timeline Properties](#setting-timeline-properties)
      - [Setting Track Properties](#setting-track-properties)
      - [Setting Clip Properties](#setting-clip-properties)
    - [Timeline Playback Controls](#timeline-playback-controls)
    - [Track List and Track Headers](#track-list-and-track-headers)
  - [Performance and Optimization](#performance-and-optimization)
    - [About Pro ler](#about-pro-ler)
    - [Using Frame Debugger](#using-frame-debugger)
    - [Diagnosing and Fixing Performance Problems](#diagnosing-and-fixing-performance-problems)
    - [Optimising Physics Performance](#optimising-physics-performance)
    - [Optimising Graphics Performance](#optimising-graphics-performance)
    - [Optimising Unity UI](#optimising-unity-ui)
    - [Memory Optimisation](#memory-optimisation)
    - [Reducing le size of build](#reducing-le-size-of-build)
- [Building 2D Apps with Unity](#building-2d-apps-with-unity)
  - [Unity for 2D](#unity-for-2d)
    - [Editor basics for 2D](#editor-basics-for-2d)
    - [2D Sorting](#2d-sorting)
  - [Using Sprites](#using-sprites)
    - [Sprite Renderer](#sprite-renderer)
    - [Sprite Editor](#sprite-editor)
    - [Sorting groups](#sorting-groups)
    - [Slicing Sprites](#slicing-sprites)
    - [Sprite Mask](#sprite-mask)
    - [Sprite Atlas](#sprite-atlas)
    - [Tilemaps](#tilemaps)
    - [Sprite sheet animations](#sprite-sheet-animations)
  - [Learn How to Use 2D Physics](#learn-how-to-use-2d-physics)
    - [Rigidbody 2D](#rigidbody-2d)
    - [Colliders 2D](#colliders-2d)
    - [Physics Material 2D](#physics-material-2d)
    - [Joints 2D](#joints-2d)
    - [Effectors 2D](#effectors-2d)
  - [More about 2D apps](#more-about-2d-apps)
    - [Types of 2D games](#types-of-2d-games)
    - [2D Skeletal Animations](#2d-skeletal-animations)
    - [Mobile and Touch Input](#mobile-and-touch-input)
    - [Optimising Mobile Applications](#optimising-mobile-applications)
- [Creating Virtual Reality Applications](#creating-virtual-reality-applications)
  - [Mobile VR App Development](#mobile-vr-app-development)
    - [Headset tracking](#headset-tracking)
    - [Controller tracking](#controller-tracking)
    - [Retrieving performance information](#retrieving-performance-information)
    - [Controller Input and Output](#controller-input-and-output)
    - [Transforming Coordinates](#transforming-coordinates)
    - [Unity XR APIs](#unity-xr-apis)
    - [Using Google Cardboard](#using-google-cardboard)
    - [Interaction in Mobile VR](#interaction-in-mobile-vr)
    - [Locomotion in Mobile VR](#locomotion-in-mobile-vr)
  - [Buildingfordi erentVRPlatformslikeOculusRift,Oculus Quest, HTC Vive etc](#buildingfordi-erentvrplatformslikeoculusriftoculus-quest-htc-vive-etc)
    - [Unity VR Interaction Toolkit](#unity-vr-interaction-toolkit)
    - [Importing Integration SDKs and Package](#importing-integration-sdks-and-package)
    - [Setting up Device](#setting-up-device)
      - [Defining Play Area for Tracking](#defining-play-area-for-tracking)
      - [User Orientation](#user-orientation)
      - [Positional and Rotational Tracking](#positional-and-rotational-tracking)
      - [Head Tracking](#head-tracking)
      - [Controllers And Custom Hands](#controllers-and-custom-hands)
    - [Moving around in VR - Teleportation](#moving-around-in-vr---teleportation)
    - [Interacting with Objects in VR](#interacting-with-objects-in-vr)
    - [UI Interaction in VR](#ui-interaction-in-vr)
    - [How to build, deploy and run?](#how-to-build-deploy-and-run)
    - [Optimizing VR app based on hardware support](#optimizing-vr-app-based-on-hardware-support)
  - [360 Video and VR](#360-video-and-vr)
    - [3-DoF and 6-DoF](#3-dof-and-6-dof)
    - [Equirectangular Projection](#equirectangular-projection)
    - [Cubemaps](#cubemaps)
    - [VR Cameras](#vr-cameras)
    - [Spatial Audio](#spatial-audio)
- [Creating Augmented Reality Applications](#creating-augmented-reality-applications)
  - [Introduction to AR](#introduction-to-ar)
    - [What is AR?](#what-is-ar)
    - [Applications and Domains](#applications-and-domains)
  - [AR Basics](#ar-basics)
    - [Tracking in AR](#tracking-in-ar)
      - [Outside-in tracking](#outside-in-tracking)
      - [Inside-out tracking](#inside-out-tracking)
      - [Motion tracking](#motion-tracking)
    - [Feature points](#feature-points)
    - [Plane-finding](#plane-finding)
    - [Estimation of Light](#estimation-of-light)
    - [Interface issues](#interface-issues)
    - [Power and size constraints in AR](#power-and-size-constraints-in-ar)
    - [Limitations of Computer Vision](#limitations-of-computer-vision)
    - [Image recognition](#image-recognition)
      - [2D Image Recognition and Tracking](#2d-image-recognition-and-tracking)
      - [3D Object Recognition and Tracking](#3d-object-recognition-and-tracking)
    - [Occlusion and shading constraints](#occlusion-and-shading-constraints)
  - [ARCore](#arcore)
    - [Surface detection](#surface-detection)
    - [Creating planes](#creating-planes)
    - [User interaction: pose and hit- testing](#user-interaction-pose-and-hit--testing)
    - [Anchor points](#anchor-points)
    - [Occlusion](#occlusion)
    - [Matching virtual light to real light](#matching-virtual-light-to-real-light)
    - [Multi-plane detection](#multi-plane-detection)
    - [Spatial mapping](#spatial-mapping)
    - [Processing needs in mobile AR](#processing-needs-in-mobile-ar)
    - [Create 3D assets for AR with tools like Google Poly and Unity](#create-3d-assets-for-ar-with-tools-like-google-poly-and-unity)
    - [SLAM (Simultaneous Localization and Mapping)](#slam-simultaneous-localization-and-mapping)
  - [AR development plugins in Unity](#ar-development-plugins-in-unity)
    - [ARKit](#arkit)
    - [Magic Leap XR Plug-in on Magic Leap](#magic-leap-xr-plug-in-on-magic-leap)
    - [Windows XR Plug-in on HoloLens](#windows-xr-plug-in-on-hololens)
    - [Vuforia](#vuforia)
    - [Wikitude SDK](#wikitude-sdk)
  - [Augmented Reality with Geolocation](#augmented-reality-with-geolocation)
    - [Mobile GPS](#mobile-gps)
    - [Compass functions](#compass-functions)

# Introduction to AR, VR & Game Development

## Building Games

### Setting up gameobject

### Adding Hero, obstacle and goal

### Adding moving enemies

### Adding platforms

### Designing levels

### Controlling player with mouse

### Adding shooter gameobject

### Adding shooting mechanics for the player

### Having score computing system

### Adding background and scrolling effect

### Creating winning screen

### Making it Multiplayer

### Computing and showing the score for both the players

## AR with Spark AR Studio

### Creating lters and masks

### Adding effects like VHS, dust, scratches

### Creating an immersive particle effect

### Working with textures and materials

### Animating 3D objects in real world

### Face Tracking Effect and Iris Tracking

### Responding to Facial Movement

### Face Gestures

## Create apps for WebVR with A-Frame

### Going through A-Frame examples

### Start with scene and transform the objects

### Importing and displaying 3D models

### Adding Textures

### Using animations

### Interaction with the objects

### Teleportation

### Using and modifying the controls

### Playing video and audio

### Controlling entities with Javascript

### Testing WebVR scenes

# C# Scripting Fundamentals in Unity

## Basics of C#

### Data types, Variables and Constants

### Conventions and Syntax

### Conditional Statements & Operators

#### If, else

#### Switch Statements

#### Ternary Operator

### Loops

### Arrays, Lists and Dictionaries

### Functions

### Scope and Access Modi ers

## Classes and Namespaces

### Static Class

### Partial Class

### Nested Class

### Inheritance

## About MonoBehaviour

### Awake and Start

### Update and FixedUpdate

### Enabling and Disabling Components

### Destroy

## Gameobject and Transform

### Activating GameObject

### Translate and Rotate

### GetComponent

### Instantiate

## Reading Inputs

### GetButton and GetKey

### GetAxis

### Mouse and Pointer Functionalities

## Vector Maths

### Vector Arithmetic

### Dot and Cross Products

### Computing Normal vector

### Projecting one vector onto the other

## Adding Movement

### Linear Interpolation

### DeltaTime

### Invoke

### Enumerations

### Quaternions

# Advanced C# Scripting

## More about Classes and Methods

### Creating Properties

### Method Overloading

### Overriding

### Interfaces

### Extension Methods

### Coroutines

### Abstract Classes

### Delegates and Events

### Statics

### Generics

### Member Hiding

### Object Pools

### Attributes

### LINQ

### Lambda Expressions

### Asynchronous Programming with Async / Await

## Data Structures

### Linked Lists

### Stacks, Queues

### Trees

## Design Patterns for App Developers

### Singleton

### Game Loop and Update Method

### Observer, Mediator, Template

## Selected topics in C#

### Exception handling

### Text Files Streaming Assets

### Playerprefs

### Editor Scripting

### Scriptable Objects

### C# Job System

### Entity Component System

# Fundamentals of 3D Application Development

## Working in 3D Space

### Unity Editor Basics

#### Creating a 3D unity project

#### Walkaround of Unity Windows

#### Using Tools

### Gameobjects and Assets

#### Creating and Positioning gameobjects

#### Importing Assets into a Project

### Prefabs

#### Con gure Prefabs for use throughout a scene

#### Nested Prefabs Prefab Variants

## Setting Up the Scene

### Camera Setup

### About Skybox

### Adjusting Lighting

#### Light Sources

## Preparing Assets for Implementation

### Creating and Using Materials

### Importing and Using Textures

#### Types of Shaders

#### Texture size best practices

### Adding Textures

### Meshes and Mesh Renderers

## Play Music In Your App

### Audio Listener

### Audio Source

## Customizing the UI

### Unity UI Components

#### Canvas and Panel

#### Button and Toggle

#### Sprites and Image

#### TextMesh Pro and Input Field

#### Slider and Scroll View

### Design UI for Multiple Resolutions

#### Layouts

#### Content Size Fitters

## Learn Unity’s Physics System

### Rigidbody

### Understanding Collisions

### Colliders and Triggers

### Velocity, Force

### Torque

### Raycast

## Controlling Animation

### Animator Setup

#### Controller

#### State Machine

#### Scripting

### Animation Clips

## Navigation and Pathfinding

### Navigation System in Unity

### Navmesh Agents

### Building and Baking Navmesh

## Building to devices

### Build Settings

### Project Settings

#### Audio

#### Editor

#### Graphics

#### Physics

#### Quality

#### Time

### Different platforms

#### Android, iOS

#### Windows, Mac, Linux

# Mastering 3D Application Development

## CamerasandE ects

### Field of View

### Occlusion Culling

### Adding Effects

#### Particle Systems

#### Writing Custom Shaders

#### Post Processing

#### Render Pipelines

### More about Lighting

#### Shadows

#### LightMapping

#### Reflection and Light Probes

#### Realtime Global Illumination

### Using More than one Camera

### Visual Effects Components

#### Lens Flare

#### Line Renderer

#### Trail Renderer

#### Billboard Renderer

#### Projector

### About ColorSpace

#### Linear

#### Gamma work ow and Textures

## Advanced Audio

### Audio Mixer

### Audio Spatializer

### Audio Filters

### Ambisonic Audio

## Importing settings

### Importing Animations

### Importing Models

## Advanced Physics System

### Joints

### Physics Material

### Character Controllers

### Multi-scene Physics

## Adding Constraints

### Using Parent

### About LookAt, Aim etc

## Creating Environments

### Creating and editing Terrains

### Trees and Tree Editor

## Adding 3D art and Animations

### Editing Animation Clips - Adding events and curves

### Humanoid and Non Humanoid Animations

### Avatar

### Rig

### Animator Controller Layer

### Avatar Mask

### Blend Trees

### Inverse Kinematics

## Using Navmesh and PathFinding

### Off-Mesh links

### Obstacles

### Navmesh Area

### Coupling Animation and Navigation

## Multiplayer Games and Apps

### Multiplayer Overview

### Setting up a multiplayer project

### Using the Network Manager

### Multiplayer APIs

## Powering Cameras with Cinemachine

### Using Virtual Cameras

### Cinemachine Brain

### 2D graphics

### Cinemachine Impulse

## Create Cinematic content using Timeline

### Using the Timeline window to record basic animation

### Timeline Preview and Timeline Selector

### Timeline Inspector

#### Setting Timeline Properties

#### Setting Track Properties

#### Setting Clip Properties

### Timeline Playback Controls

### Track List and Track Headers

## Performance and Optimization

### About Pro ler

### Using Frame Debugger

### Diagnosing and Fixing Performance Problems

### Optimising Physics Performance

### Optimising Graphics Performance

### Optimising Unity UI

### Memory Optimisation

### Reducing le size of build

# Building 2D Apps with Unity

## Unity for 2D

### Editor basics for 2D

### 2D Sorting

## Using Sprites

### Sprite Renderer

### Sprite Editor

### Sorting groups

### Slicing Sprites

### Sprite Mask

### Sprite Atlas

### Tilemaps

### Sprite sheet animations

## Learn How to Use 2D Physics

### Rigidbody 2D

### Colliders 2D

### Physics Material 2D

### Joints 2D

### Effectors 2D

## More about 2D apps

### Types of 2D games

### 2D Skeletal Animations

### Mobile and Touch Input

### Optimising Mobile Applications

# Creating Virtual Reality Applications

## Mobile VR App Development

### Headset tracking

### Controller tracking

### Retrieving performance information

### Controller Input and Output

### Transforming Coordinates

### Unity XR APIs

### Using Google Cardboard

### Interaction in Mobile VR

### Locomotion in Mobile VR

## Buildingfordi erentVRPlatformslikeOculusRift,Oculus Quest, HTC Vive etc

### Unity VR Interaction Toolkit

### Importing Integration SDKs and Package

### Setting up Device

#### Defining Play Area for Tracking

#### User Orientation

#### Positional and Rotational Tracking

#### Head Tracking

#### Controllers And Custom Hands

### Moving around in VR - Teleportation

### Interacting with Objects in VR

### UI Interaction in VR

### How to build, deploy and run?

### Optimizing VR app based on hardware support

## 360 Video and VR

### 3-DoF and 6-DoF

### Equirectangular Projection

### Cubemaps

### VR Cameras

### Spatial Audio

# Creating Augmented Reality Applications

## Introduction to AR

### What is AR?

### Applications and Domains

## AR Basics

### Tracking in AR

#### Outside-in tracking

#### Inside-out tracking

#### Motion tracking

### Feature points

### Plane-finding

### Estimation of Light

### Interface issues

### Power and size constraints in AR

### Limitations of Computer Vision

### Image recognition

#### 2D Image Recognition and Tracking

#### 3D Object Recognition and Tracking

### Occlusion and shading constraints

## ARCore

### Surface detection

### Creating planes

### User interaction: pose and hit- testing

### Anchor points

### Occlusion

### Matching virtual light to real light

### Multi-plane detection

### Spatial mapping

### Processing needs in mobile AR

### Create 3D assets for AR with tools like Google Poly and Unity

### SLAM (Simultaneous Localization and Mapping)

## AR development plugins in Unity

### ARKit

### Magic Leap XR Plug-in on Magic Leap

### Windows XR Plug-in on HoloLens

### Vuforia

### Wikitude SDK

## Augmented Reality with Geolocation

### Mobile GPS

### Compass functions
