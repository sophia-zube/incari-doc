# Animation

## Introduction

The **Animation Nodes** are used to control **Animation Blocks** created in the [**Animation Editor**](../../../modules/animation-editor.md). They allow the user to play, pause, or stop **Animations**.

### Instance ID

Each **Animation Block** has an **Instance ID**, which is a unique identifier that can be set with the [**Create CustomID Node**](../utilities/createcustomid.md) in the `Instance ID` **Input Socket**. The **Instance ID** is assigned when an **Animation** starts playing, triggered by the [**Play Animation Node**](playanimation.md), and it is then used to indicate to either the [**Pause Animation**](pauseanimation.md) or [**Stop Animation Node**](stopanimation.md) which **Animation** shall be paused or stopped. 

It is also possible to use an **Object ID** as an **Instance ID**.

The default **Instance ID** for **Animations** is 42.



## Contents

* [**Pause Animation**](pauseanimation.md)
* [**Play Animation**](playanimation.md)
* [**Stop Animation**](stopanimation.md)

