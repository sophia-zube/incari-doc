# Animation

## Introduction

The **Animation Nodes** are used to control **Animation Blocks** created in the [**Animation Editor**](../../../modules/animation-editor.md). They allow the user to play, pause, or stop **Animations**.

### Instance ID

Each **Animation Block** has an **Instance ID**, which is a unique identifier that can be set with the [**Create CustomID Node**](../utilities/createcustomid.md) in the `Instance ID` **Input Socket**. The **Instance ID** is assigned when an **Animation** starts playing, triggered by the [**Play Animation Node**](playanimation.md). The **Instance ID** then tells either the [**Pause Animation**](pauseanimation.md) or [**Stop Animation Node**](stopanimation.md) which **Animation** is meant to be paused or stopped, respectively. 

Another use of the **Instance ID** is to distinguish between **Animations**. Two or more **Animations** without an **Instance ID** assigned with the [**Create CustomID Node**](../utilities/createcustomid.md) will have the same default **Instance ID** and be seen as the same by the system, even if played in parallel.

It is also possible to use an **Object ID** as an **Instance ID**.

The default **Instance ID** for **Animations** is 42.



## Contents

* [**Pause Animation**](pauseanimation.md)
* [**Play Animation**](playanimation.md)
* [**Stop Animation**](stopanimation.md)

