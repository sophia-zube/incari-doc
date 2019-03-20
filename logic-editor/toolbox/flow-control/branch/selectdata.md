# SelectData

### Overview

Used to consolidate multiple values of the same [data-type](../../../data-types/) and their corresponding pulses into a single value and pulse. If [**Branch** ](branch.md)is the _divergence_ of logical outcomes, then **SelectData** can be thought of as the _convergence_.

### Inputs and Outputs

![The SelectData node in the Logic Editor&apos;s graph.](../../../../.gitbook/assets/selectdata-node.png)

The **SelectData** node has two **Pulse** inputs and two data inputs.

* **Pulse A** - A **Pulse** input, which corresponds to the **A** data input.
* **A** - A data input, which corresponds to the **Pulse A** logic input.
* **Pulse B** - A **Pulse** input, which corresponds to the **A** data input.
* **B** - A data input, which corresponds to the **Pulse B** logic input.

### Attributes

**SelectData** only has a single attribute in the logic editor, which defines the type of input [**data**](../../../data-types/).

### Usage - Example 1

Although nodes in INCARI accept multiple _pulse_ input connections, they only accept single _data_ input connections. When we have multiple logic paths, producing multiple possible values for the same data-type and we want to do something with that data, regardless of how it was evaluated, we need a way of converging the value of our data and logic into a single branch.

#### Problem

Below we print a message to the console, stating which key is pressed, A or B. Without **SelectData**, we have need to use two Console nodes for each of the messages. This may seem like a small issue, but in more complex logic trees, where we have a multitude of branching and diverging paths, we would potentially end up with a lot of unnecessary, duplicated logic.

![Without using SelectData we need have two logic paths with duplicated Console nodes. ](../../../../.gitbook/assets/selectdata-problem%20%281%29.png)

#### Solution

By using **SelectData**, we can bring our logic into a single branch and avoid many of the issues discussed above.

![SelectData allows us to converge our logic paths.](../../../../.gitbook/assets/selectdata-solution.png)

The benefit of this method becomes even more apparent when we have more paths. We can use multiple **SelectData** nodes to converge our **Pulses** and now we are using just one **Console** node, rather than four.

![Having the ability to converge our logic helps us keep our node graph much more tidy, maintainable and error-resistant.](../../../../.gitbook/assets/selectdata-solution-2.png)

