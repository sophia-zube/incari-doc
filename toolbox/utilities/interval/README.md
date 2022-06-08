# Interval

## Introduction

The **Interval Nodes** provide a means for the user to start or reset an **Interval**. An **Interval** is defined by a period of time, in this case a number of seconds. The **Logic** attached to this **Interval** will be repeated over and over every *X* seconds until it is stopped, or reset.

For example, if the **Start Interval** **Node** is triggered, the **Logic** attached to the **Output Pulse Socket** will occur every 5 seconds, assuming 5 seconds is entered in the `Seconds` **Input**. If a **Reset Interval Node** is triggered, the **OnReset Output** of **Start Interval** will be activated and stop the **Interval**, until the user wishes to start it again. 

## Contents

* [**Reset Interval**](resetinterval.md)
* [**Start Interval**](startinterval.md)


