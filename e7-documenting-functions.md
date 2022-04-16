`logout()`\
Logs out the current user.<br><br>

`getNumberFriends()`\
Returns the number of friends that the current user has.<br><br>

`requestFriend(username)`\
Sends a friend request to the specified user.\
**Parameter:**
* username
    * **Type:** string.
    * Username of the user to send the friend request to.<br><br>

`post(statusUpdate)`\
Posts a status update.\
Allowed length is up to 1000 characters. Returns information on whether the status was updated or not.\
**Parameter:**
* `statusUpdate`
    * **Type:** string.
    * Status update to be posted.

**Returns:**
* **Type:** boolean.
* `true` if the post succeeds to be posted.
* `false` if the post fails to be posted.<br><br>

`like(postId, likeType)`\
Likes the specified post.\
Returns information on whether the interaction succeeded.\
**Parameters:**
* `postID`
    * **Type:** number.
    * ID of the post to be liked.
* `likeType`
    * **Type:** string.
    * The type of interaction, the meaning that the current user assigns to it.
    * Valid values: "Like", "Love", "Empathy".

**Returns**
* Type: boolean.
    * `true` if the interaction succeeds to be logged in the post.
    * `false` if the interaction fails to be logged in the post.
<br><br><br>

What the fictional engineering team provided:
* logout() – For logging out the current user.
* getNumberFriends() – Gets the number of friends the current user has.
* requestFriend(username) – This sends a friend request to a user.
* post(statusUpdate) – Used to post a status update. The status update can be up to 1000 characters long. Returns true if the post succeeds and false if the post fails.
* like(postId, likeType) – Likes a post. The post is specified by the ID, which is an integer. The likeType can have one of these values: "Like", "Love", "Empathy". Returns true if the like succeeds and false if the like fails.
<br><br><br>

*Exercise 7 – Documenting Functions*, from this [course].

[course]: https://www.udemy.com/course/coding-for-writers-1-basic-programming/