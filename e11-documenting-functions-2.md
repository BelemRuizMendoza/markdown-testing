## `safeMode(enable)`
Enables or disables the safe mode.
### Parameter
* `enable`
    * **Type:** boolean.
    * `true` for enabled; `false` for disabled.
<br>

## `getPremiumMode()`
Returns whether the user has paid for the premium service.
### Returns
* **Type:** boolean.
* `true` for an active premium service; otherwise, `false`.
<br>

## `setTimeout(timeout)`
Sets the time to wait for a response before timing out.
### Parameter
* `timeout`
    * **Type:** number.
    * The time to wait for a response before timing out.
    * Measured in milliseconds.
<br>

## `newEvent(calendarId)`
Creates a new event for the specified calendar.
### Parameter
* `calendarId`
    * **Type:** number.
    * The ID of the calendar.
### Returns
* **Type:** number.
* The ID of the new event.
<br>

## `getDirections(latitude, longitude, directionsCallback)`
Returns the directions to go from the current location to the specified destination point.
### Parameter
* `latitude`
    * **Type:** number.
    * Latitude of the destination point, in degrees.
* `longitude`
    * **Type:** number.
    * Longitude of the destination point, in degrees.
* `directionsCallback`
    * **Type:** function.
    * Called when the directions are returned from the server. Contains the string parameter `directions`, which has the directions on how to go from the current location to the specified destination point.
### See also:
* [`directionsCallback()`]
<br>

## `createTransaction(amount)`
Creates a new transaction.
### Parameter
* `amount`
    * **Type:** number.
    * Total amount of the transaction.
    * Displayed in the default currency.
### Returns
* **Type:** string.
* The ID of the new transaction.
### See also:
* [`getTransaction()`]
* [`deleteTransaction()`]
<br>

[`directionsCallback()`]: https://justaninventedurl.com
[`getTransaction()`]: https://secondinventedurl.com
[`deleteTransaction()`]: https://thirdinventedurl.com
<br><br><br>

*Exercise 11 – Documenting Functions 2*, from this [course].

[course]: https://www.udemy.com/course/coding-for-writers-1-basic-programming/