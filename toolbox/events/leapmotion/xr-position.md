# Overview

![The XR Position Node.](../../../.gitbook/assets/xrpositionnode.png)

The **XR Position Node** returns the position in 3D space of the tracked entity in some extended reality (*XR*) incorporating *Leap Motion*.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `XR Position` | **Vector3** |Returns a 3-dimensional vector containing the $$X$$, $$Y$$, and $$Z$$ values of the current position.|



