# Prefabs

In most HMI projects you will create, the likelihood of having different variants of a component is quite high. Although this component can be anything from list items to search boxes, for this demo we will be focusing on arguably the most prominent one: buttons.

## Overview

As part of this project you will:

1. Create a simple button in **Incari Studio**.

2. Turn your basic button into a customizable **Prefab** with **Logic**.

3. Use **Prefabs** to build a complex **Project** with just a few clicks.

**What is a prefab?**

Glad you asked. A **Prefab** in **Incari Studio** is a reusable component that encompasses its own **Logic**, design and behavior independently from the rest of the **Project**. This means they can be transferred between **Projects**, and take many shapes. For more information, see [**Prefabs**](../objects-and-types/prefabs/README.md).

**Before you start**

Download **Assets**.

## 1. Creating a Simple button

Let’s imagine a generic, rounded rectangle button that can have multiple different icons in the middle - something you would see in a lot of HMI systems. This can even be used to build a custom keyboard - though we already have a customizable On-Screen-Keyboard node in Incari, so you don’t have to!

Our button will have three states: resting, hover and pressed.

![Button states.]()

Also, for this demo, let’s say we need 4 different buttons: Wi-Fi, Bluetooth, Cellular, GPS and Mic. This is a common layout that you might see everywhere from your phone to your car. So, these are the final buttons we want to have:

![]()