# The Float and Vector Data Types

As discussed earlier, there are various different **Data Types** available in INCARI. We are already familiar with **Integers**, but we haven't yet worked with **Vectors** or **Floats**.

**Floats**, like **Integers**, are a **Numerical Type**, and can be used for various **Math Operations**. The difference with **Floats**, however, is that **Integers** can only be _whole_ numbers, while **Floats** are _floating-point_ numbers \(can have a decimal point\). An **Integer** is useful for measuring the number of people in a company, for instance, because you can't have half a person. If you wanted to record the height of a wall, though, we would need a more accurate type of measurement. This is where **Floats** are favourable to **Integers**.

A **Vector Data Type** \(**Vector2**, **Vector3**, **Vector4**\) is essentially a set of **Floats**, with the number at the end of the **Type**'s name, representing how many **Floats** it is composed of. This makes **Vector Types** perfect for storing **Transformation** information, and whenever you adjust the **Transformation Attribute** of an **Object**, you are essentially modifying a **Vector3**.

With this in mind, consider that we are going to be dynamically changing the **Rotation Attribute** of our needle graphic, which is a **Vector3 \(**representing the rotation on each of the X, Y and Z axes\). At the moment, our **Output** from the **RangeMapper** is of the **Integer Data Type**. We

