> ## View the entire tutorial on [GameDev Resources](https://gamedev-resources.com/implementing-touch-with-input-systems-enhanced-touch-api/).

# Listen for the Input System's Action events via C#

> **This tutorial was created with Unity version 2019.2.**

In certain scenarios it may be beneficial to listen for Input System Action callbacks via C#, rather than using the built in Player Input component. This tutorial will walk through writing an `InputManager` script to listen for and route such events. 

## Prerequisites
This is a continuation of the [How to make a configurable camera with the new Input System](https://gamedev-resources.com/tutorials-2/) tutorial series, which covers fundamental knowledge of the Input System. While not recommended, (unless you are already familiar with the Input System) you can skip tutorial by cloning the starterProject in this section of the repository.

## Learning Outcomes

1. Understand the different Input System Action callbacks and how to hook them up via C# 

## Resources
1. Comments, concerns and/or questions can be posted [here](https://github.com/Yecats/GameDevTutorials/issues/4).
2. Part 1 Tutorial: [How to make a configurable camera with the new Input System](../How-to-make-a-configurable-camera-with-the-new-Input-System)
2.	Input System [documentation](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.0/manual/index.html) and [GitHub repository](https://github.com/Unity-Technologies/InputSystem).
3. [Introducing the new Input System - Unite Copenhagen Video](https://youtu.be/hw3Gk5PoZ6A)
1. This project uses the [Low Poly: Free Pack](https://www.assetstore.unity3d.com/en/#!/content/58821) by AxeyWorks.

