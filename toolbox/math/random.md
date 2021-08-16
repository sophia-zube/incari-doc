# Overview

![The Random Node.](../../.gitbook/assets/node-random.png)

The **Random** **Node** generates a random outcome, usually a number.

This **Node** can be set to three different `Modes` (**Advanced**, **Expert**, and **Standard**). Each of these `Modes` offers a different set of **Attributes** that are explained below.

# Attributes

Each `Mode` has a different set of **Attributes**. The `Modes` are: [**Advanced**](random.md#advanced), [**Expert**](random.md#expert), and [**Standard**](random.md#expert).

## Advanced

### Generator

|Attribute|Type|Description|
|---|---|---|
| `Is deterministic` | **Bool** | Whether the random number generator is deterministic or not. |
| `Seed` | **Int** (*only available when `Is Deterministic` is set to _true_*)| The `Seed` to use for the deterministic random number generator. |

### Distribution

This **Mode** has a **Drop-down** menu from which the _probability distribution_ used for the random number generator can be chosen. Each option offers then its own set of **Attributes** with the _probability distribution_ parameters.

|Attribute|Type|Description|
|---|---|---|
| `Distribution` | **Drop-down** | The _probability distribution_ that the random number generator will use. |

Next, the **Attributes** for each _probability distribution_ are described. For each _probability distribution_, the link to its corresponding Wikipedia entry is given.

* [Bernoulli](https://en.wikipedia.org/wiki/Bernoulli_distribution)

_Probability distribution_ of a _random variable_ that can take two values: _true_, with probability p; and _false_, with probability 1-p.
When this distribution is chosen, the outcome of the **Node** is a **Boolean**.

|Attribute|Type|Description|
|---|---|---|
| `Probability of 'true'` | **Float** (_between 0 and 1_) | The probability that the outcome will be _true_. |

*  [Binomial](https://en.wikipedia.org/wiki/Binomial_distribution)

_Probability distribution_ of the number of successes in a sequence of independent experiment, each with two possible outcomes: success and failure. The parameters for this _probability distribution_ are the number of experiments and the probability of a successful outcome in each.

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether the outcome will be an **Int** or **Byte**.|
| `Probability of 'true'` | **Float** | The probability that the outcome of each trial is _true_. |
| `Number of trials` | **Int** | The number of independent experiments, each with probability of success `Probability of 'true'`. |

*  [Normal](https://en.wikipedia.org/wiki/Normal_distribution)



|Attribute|Type|Description|
|---|---|---|
| `Mean` | **Float** | The mean value of the distribution. |
| `Standard deviation` | **Float** | The standard deviation of the distribution. |

*  [Poisson](https://en.wikipedia.org/wiki/Poisson_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Wheter the outcome will be an **Int** or **Byte**. |
| `Mean` | **Float** | The mean value of the distribution. |

*  Uniform

_Probability distribution_ in which all the values in an interval are equally likely to be drawn. It can either be [continuous](https://en.wikipedia.org/wiki/Continuous_uniform_distribution) or [discrete](https://en.wikipedia.org/wiki/Discrete_uniform_distribution).

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether an **Int**, **Float**, or **Byte** will be generated. |
| `Minimum` | _Defined in the `Data Type` **Attribute**_ | The lower bound of the interval from which the random number will be extracted.|
| `Maximum` | _Defined in the `Data Type` **Attribute**_ | The upper bound of the interval from which the random number will be extracted.|




## Expert 

### Generator

|Attribute|Type|Description|
|---|---|---|
| `Generator` | **Drop-down** | |
| `Seed` | **Int** (*not available for non_deterministic `Generator`*) | The `Seed` to use for the random number generator. |

### Distribution

This **Mode** has a **Drop-down** menu from which the _probability distribution_ used for the random number generator can be chosen. Each option offers then its own set of **Attributes**, which are detailed below.

|Attribute|Type|Description|
|---|---|---|
| `Distribution` | **Drop-down** | The _probability distribution_ that the random number generator will use. |

*  [Bernoulli](https://en.wikipedia.org/wiki/Bernoulli_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Probability of 'true'` | **Float** (_between 0 and 1_) | The probability that the outcome will be _true_. |

*  [Binomial](https://en.wikipedia.org/wiki/Binomial_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether the outcome will be an **Int** or **Byte**.|
| `Probability of 'true'` | **Float** | The probability that the outcome of each trial is _true_. |
| `Number of trials` | **Int** | The number of independent experiments performed, each with probability of success `Probability of 'true'`. |

*  [Cauchy](https://en.wikipedia.org/wiki/Cauchy_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Location` | **Float** | |
| `Scale` | **Float** | |

*  [Chi_Squared](https://en.wikipedia.org/wiki/Chi-squared_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Degrees of freedom` | **Float** |  |

*  [Exponential](https://en.wikipedia.org/wiki/Exponential_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Rate` | **Float** |  |

*  [Extreme_Value](https://en.wikipedia.org/wiki/Generalized_extreme_value_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Location` | **Float** | |
| `Scale` | **Float** | |

*  [Fisher_F](https://en.wikipedia.org/wiki/F-distribution)

|Attribute|Type|Description|
|---|---|---|
| `Denominator Dof` | **Float** | |
| `Numerator DoF` | **Float** | |

*  [Gamma](https://en.wikipedia.org/wiki/Gamma_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Shape` | **Float** | |
| `Scale` | **Float** | |

*  [Geometric](https://en.wikipedia.org/wiki/Geometric_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | |
| `Probability of 'true'` | **Float** (_between 0 and 1_) | |

*  [Lognormal](https://en.wikipedia.org/wiki/Log-normal_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Mean` | **Float** | |
| `Standard deviation` | **Float** | |

*  [Negative_Binomial](https://en.wikipedia.org/wiki/Negative_binomial_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | |
| `Probability of 'true'` | **Float** (_between 0 and 1_) | |
| `Number of trials` | **Float** | |

*  [Normal](https://en.wikipedia.org/wiki/Normal_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Mean` | **Float** | The mean value of the distribution. |
| `Standard deviation` | **Float** | The standard deviation of the distribution. |

*  [Poisson](https://en.wikipedia.org/wiki/Poisson_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Wheter the outcome will be an **Int** or **Byte**. |
| `Mean` | **Float** | The mean value of the distribution. |


*  [Student_T](https://en.wikipedia.org/wiki/Student%27s_t-distribution)

|Attribute|Type|Description|
|---|---|---|
| `Degrees of freedom` | **Float** | |

*  Uniform

_Probability distribution_ in which all the values in an interval are equally likely to be drawn. It can either be [continuous](https://en.wikipedia.org/wiki/Continuous_uniform_distribution) or [discrete](https://en.wikipedia.org/wiki/Discrete_uniform_distribution).

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether an **Int**, **Float**, or **Byte** will be generated. |
| `Minimum` | _Defined in the `Data Type` **Attribute**_ | The lower bound of the interval from which the random number will be extracted.|
| `Maximum` | _Defined in the `Data Type` **Attribute**_ | The upper bound of the interval from which the random number will be extracted.|

*  [Weibull](https://en.wikipedia.org/wiki/Weibull_distribution)

|Attribute|Type|Description|
|---|---|---|
| `Shape` | **Float** | |
| `Scale` | **Float** | |



## Standard

### Distribution

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether an **Int**, **Float**, or **Byte** will be generated. |
| `Minimum` | _Defined in the `Data Type` **Attribute**_ | The lower bound of the interval from which the random number will be extracted.|
| `Maximum` | _Defined in the `Data Type` **Attribute**_ | The upper bound of the interval from which the random number will be extracted.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Output` | _Defined in the `Data Type` **Attribute**_ | The random number that was generated. |


# External Links

