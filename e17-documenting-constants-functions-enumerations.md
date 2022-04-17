## Constants Documentation
|Name|Description|Type|
|:---|:----------|:---|
|`exclamationResponses`|Responses to use when the user’s line ends with an exclamation point.|Array of strings|
|`genericResponses`|Responses to use when no better option is available.|Array of strings|
|`povSwitches`|Mapping between first person and second person words.|Object|
|`questionResponses`|Responses to use when the user’s line ends with a question mark.|Array of strings|
|`questionStarts`|First few words of a question.|Array of strings|
<br><br>

## Functions Documentation
### `createQuestion(patientLine)`
Returns a question based on the patient’s line.
#### **Parameter**
* `patientLine`
    * Type: string.
    * Patient’s text to respond to.
#### **Returns**
* Type: string.
* Question based on the patient’s line.
<br>

### `lastChar(myString)`
Returns the last character in a string.
#### **Parameter**
* `myString`
    * Type: string.
    * String to return last character for.
#### **Returns**
* Type: string.
* Last character of the string.
<br>

### `randomElement(myArray)`
Returns a random element of an array
#### **Parameter**
* `myArray`
    * Type: array.
    * Array with one or more elements.
#### **Returns**
* Type: whatever is in the array.
* Random element from the array.
<br><br>

## Enumeration Documentation
|Property Name|Description|Value|
|:------------|:----------|:---:|
|`Generic`|Generic answer that does not use the patient response.|0|
|`Question`|Answer to a question.|1|
|`Exclamation`|Answer to a patient response that ends with an exclamation point.|2|
|`PointOfView`|Answer that uses the patient response by switching the point of view from first person to second person.|3|
<br><br><br>

*Exercise 17 – Documenting Constants, Functions, and Enumerations*, from this [course].

[course]: https://www.udemy.com/course/coding-for-writers-1-basic-programming/