---
layout: post
title: Interactive 3D Graphics
description: Personal Notes On The Udacity Course
image: assets/images/Interactive3dGraphics.jpg
---

# Lesson 1 - Introduction
## Introduction
Firstly, Eric Haines is teaching this course, and whenever I take a course online I ALWAYS do some research on the instructor, verifying the veracity of a man's word should be a given. "It was the age of information.. it was the age of misinformation.."
Eric (from what i've gathered) is a true OG in the computer graphics arena, working on computer graphics since 1983.
In this course Eric says although the hardware and languages/paradigms will inevitably change, he'll cover what makes computer graphics tick. 
The underlying principles he'll cover will give students a firm foundation in the field.
Also, thanks to webgl, the beauty of computer graphics can be witnessed by just a web browser, which at the level it is now would have been impossible just a few years ago.

## Interactive 3D Rendering
Rendering = depiction
To render means to create an image
An artist can render a scene by painting it
An architect can render a building in perspective.
In 3d Graphics, things are defined in a 3d dimensional world, defined by objects materials, lights and camera, used to render onto a 2 dimensional screen, the monitor becoming a window into this world you create.

In this video we breakdown what it is exactly we mean by Interactive 3d Graphics. I suppose it would be prudent of us to define the context by which we will be exploring the matter in.

Users actions affect something in a 3D Virtual world
ie. possibly affectin objects and lighting as you go.

Neuroscience tidbit: According to james gellen, about more than a quarter is involved with processing visual images.

Related: Image Processing- using comp to analyze images and extract mathematical descriptions.

## Quiz 1
Correct answer is just computer games call of duty and world of warcraft, as all else are either not in 3d, or not interactive, or are neither 3d nor interactive.

## WebGL Setup
It's 2017. 

## Core Ideas
Points   - Refresh Rate & FPS
        - The Eye, PinHole Camera, View Frustum
        - Light: Physical and Virtual
        - Graphics Pipeline
        - Painters Alg & Z Buffer Alg

## Interactivity and FPS
6FPS is about the minimum for being considered interactive, in accordance to the guidelines we set regarding our definition aforementioned.

##FPS & Refresh Rate
Videogames: 30 or 60FPS (tied to refresh rate of monitors)
Film: motion blur

##Quiz 2: Math Refresher

## CPU Cycles
This regards the speed of a given processor to the amount of computational cycles it must undergo to render a given interactive 3d graphic
## The Eye
Light travels through pupil and makes contact with the retina in the retina in the rear (rods and cones)
## Screen Door
The task in 3d computer graphics is to define a world and then best figure out what light comes from each direction and so forms an image.
## 3d Scene
This lesson describes what comprises a scene, namely, Objects, which are a 3d geometry have a material associated to them.
Lights, which as we spoke about in the previous lessons is a critical consideration.
And Camera, which is important for the same reason as the Lights
##  Quiz: How Many Pixels
In this quiz we basically calculate how many computations it takes for a given amount of pixels to be rendered.
## Light & Rendering
This lesson is actually a very interesting and brings up important points about the practicality of approach for rendering in terms of sheer computing power
## How Many Computers
This lesson basically expounds on the previous lesson.
## Reversing the Process
So expounding on the Light & Rendering lesson, this lesson talks about the simplifying assumptions made in computer graphics.
1. Only photons that reach the camera are the ones needed to make the image. Meaning ideally these are the only ones we would like to compute. We essentially reverse the notion of photon propagation from source to that of the camera. 
2. Sum up Direct lighting.We cast a ray of light from the camera eye, through each pixel to see whats out there when a surface is seen at a pixel we then compute the direct effect of each light at that surface add up all the light contributions and you have a reasonable light approximation of what the surface looks like 
3. Given this idea, nothing blocks a photon. every surface is considered visible to a light unless it faces away from that light source. aka No objects cast shadows. 

## History of the Teapot
Self Explanatory

## Simple Materials
Light reflected off chrome ball wont work
Wooden ball is doable
Light bulb works too, its bright.
Finally a glass ball would pick up light contributions from objects in the scene.

## A Jog Down The Pipeline
## Pipeline Parallelism 
## Advanced Box Factory
## Parallelism
## Bottleneck
## Stalling and Starving
## Painter's Algorithm
## Flawed Painting
## Z-Buffer
## How the Z-Buffer Works
## Z-Buffer Optimization
## WebGL and three.js
## Tricky Question
## Demo: Rendering Mode 0
## Demo: Rendering Mode 1
## Different Rendering Options
## Conclusion
# Lesson 1: Problem Set
## Frame Skipping
## What Is Not Paintable?
## FPS vs. Milliseconds
## Rendering Costs
## Firefly
## Light Field Dimensions
## First Programming Exercises
# Interview: 3D Modelling
## Making Virtual Things Real
## Jesse Harrington AU at Autodesk
## How 3D Printing Works
## Any Shape Can Be Made
## Complexity Is Free
## 3D Printing Materials
## Design Process 
## Problems and Future of 3D Printing
# Lesson 2: Points, Vectors, & Meshes

