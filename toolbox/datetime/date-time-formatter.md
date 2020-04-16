# Overview

![](../../.gitbook/assets/node-date-time-formatter.png)

**Date Time Formatter** outputs a *date* and/or *time* in a specified format. By using a combination of special *format characters*, many different date/time formats can be created. This is used mostly for localization, however, it could also be used for formatting based on user preferences.

For more information about *formatting strings*, please see the external links at the [bottom of this page](#external-links).

# Attributes
## Input

|Attribute|Type|Description|
|---|---|---|
|`Default Timezone`|**Drop-down**|The timezone that will be used, which is an offset of the UTC.|
|`Default DST`|**Drop-down**|Determines whether or not Daylight Savings Time is taken into account.|

## Output

|Attribute|Type|Description|
|---|---|---|
|`Format Examples`|**Drop-down**|A selection of pre-defined formats. By selecting `Custom`, you can create a custom *formatting string*.|
|`Custom Format`|**String**|The *formatting string* which will determine how the date and/or time is represented.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`UTC Unix (ms)`|**Int**|The UTC in Unix format.|
|`Timezone Offset (ms)`|**Int**|The time offset in milliseconds.|
|`DST`|**Bool**|Determines whether or not Daylight Savings Time is taken into account.|
|`Format`|**String**|The *formatting string* which will determine how the date and/or time is represented.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**String**|The formatted date/time.|

# See Also

- [**DateTime**](README.md)
- [**Timezone Value**](timezone-value.md)
- [**Now (UTC)**](now-utc.md)

# External Links

- [*Formatting Date and Time*](https://wordpress.org/support/article/formatting-date-and-time/) on WordPress.org.
- [*PHP: date - Manual*](https://www.php.net/manual/en/function.date.php) on PHP.net.
- [*UTC - The World's Time Standard*](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.