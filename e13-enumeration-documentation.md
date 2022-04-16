Let’s say we were creating a Learning Management System. There is an enumeration to cover the roles that users can be in: student, teacher, assistant teacher, and administrator.

```js
const Role =    {
Student: 0,
AssistTeacher: 1,
Teacher: 2,
Admin: 3 
                };
```
<br>

## Developer Notes
* Students can sign up for courses and submit assignments.
* Assistant teachers can grade assignments.
* Teachers can grade assignments and submit final grades.
* Admins can do anything, including creating and deleting courses.
***
<br>

Available user roles in the Learning Management System (LMS).
|Property Name|Description|Value|
|:------------|:----------|:---:|
|`Student`|*Student role.* Allowed to sign up for courses and submit assignments.|0|
|`AssistTeacher`|*Assistant teacher role.* Able to grade assignments.|1|
|`Teacher`|*Teacher role.* Can grade assignments and submit final grades.|2|
|`Admin`|*Administrator role.* Has permission to perform all actions, including creation and deletion of courses.|3|
<br><br><br>

*Exercise 13 – Documenting Enumerations*, from this [course].

[course]: https://www.udemy.com/course/coding-for-writers-1-basic-programming/