# CAN


![The CAN Settings.](../../.gitbook/assets/projectsettscan2023real.png)

The **CAN Settings** cover the necessary data to provide functionality to the [**CAN Nodes**](../../toolbox/communication/can/README.md).

`Name` is an identifying name chosen at the user's discretion. This will show up in the **Nodes** as a choice for the `Configuration` **Attribute**.

`Baud Rate (Windows - PCAN)` is the speed of the communication for the channel. More information about this metric can be found in the **External Links** section.

`Channel (Windows - PCAN)` is the USB port that _CAN_ is connected to on _Windows_.

Furthermore, the `Channel` and `Interface` can both be specified, in the case that the user's platform is different than the target platform. If there is no difference in platforms, only one needs to be filled in.

`Interface (Linux - SocketCAN)` is the identifying name of the _CAN_ Bus. _Virtual CAN_ is also possible within **Incari**. This is only used for Linux.

A `DBC File` needs to be uploaded and selected. This `DBC File` is a vital part of the **CAN** protocol, as it stores all data regarding the connections between devices.

`Is Autostart` can be enabled or disabled and dictates when the channel is run (from the beginning of an application's life cycle or when the appropriate **Nodes** are used).

<!-- Please note that this version of **Incari** only supports the [*base (or standard) frame format*](https://en.wikipedia.org/wiki/CAN_bus#Base_frame_format). -->

It is worth noting that **Incari** supports both the [*base (or standard) frame format*](https://en.wikipedia.org/wiki/CAN_bus#Base_frame_format) and the [*extended frame format*](https://en.wikipedia.org/wiki/CAN_bus#Extended_frame_format).


## See Also

* [**CAN Nodes**](../toolbox/communication/can/)

## External Links

* More information on the [_Baud metric_](https://en.wikipedia.org/wiki/Baud).