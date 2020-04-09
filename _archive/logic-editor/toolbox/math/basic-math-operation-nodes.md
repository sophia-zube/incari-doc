# Basic Math Operation Nodes

## Add

Similar to the `+` operator in most programming languages, the Add node takes two inputs `a` and `b` of the same numerical type and returns their sum.

### Valid Types

* [Byte](../../data-types/byte.md)
* [Float](../../data-types/float.md)
* [Int](../../data-types/int.md)
* Matrix3x3
* Matrix4x4
* [Vector2](../../data-types/vector2.md)
* [Vector3](../../data-types/vector3.md)
* [Vector4](../../data-types/vector4.md)

## Subtract

Similar to the `-` operator in most programming languages, the Subtract node takes two inputs `a` and `b` of the same numerical type and returns the result of value `a` minus value `b`.

### Valid Types

* [Byte](../../data-types/byte.md)
* [Float](../../data-types/float.md)
* [Int](../../data-types/int.md)
* Matrix3x3
* Matrix4x4
* [Vector2](../../data-types/vector2.md)
* [Vector3](../../data-types/vector3.md)
* [Vector4](../../data-types/vector4.md)

## Divide

Similar to the `/` operator in most programming languages, the Divide node takes two dividable inputs `a` \(_dividend_\) and `b` \(_divisor_\) of the same numerical type, and returns the value of `a` divided `b`. 

### Valid Types

* [Byte](../../data-types/byte.md)
* [Float](../../data-types/float.md)
* [Int](../../data-types/int.md)
* [Vector2](../../data-types/vector2.md)
* [Vector3](../../data-types/vector3.md)
* [Vector4](../../data-types/vector4.md)

### Note on Dividing Integers

Because the result of dividing 2 [integers ](../../data-types/int.md)doesn't always return an [integer](../../data-types/int.md), [Euclidean division]() is used to return the _quotient_, meaning that the result of the division will be rounded _down_ to the nearest [integer](../../data-types/int.md). If this isn't the desired behaviour, both the `a` \(_dividend_\) and `b` \(_divisor_\) must first be converted to [floats](../../data-types/float.md), using the Conversion node. 

## Multiply

Similar to the `*` operator in most programming languages, the Multiply node takes two inputs `a` \(_multiplicand_\) and `b` \(_multiplier_\) of the same numerical type, and returns the _product_ of `a` multiplied by `b`. 

### Valid Types

* [Byte](../../data-types/byte.md)
* [Float](../../data-types/float.md)
* [Int](../../data-types/int.md)
* Matrix3x3
* Matrix4x4
* [Vector2](../../data-types/vector2.md)
* [Vector3](../../data-types/vector3.md)
* [Vector4](../../data-types/vector4.md)

