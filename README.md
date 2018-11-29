# manage-users

## installation

    npm install users-management
## Usage

By popular demand, `users-management`!

```js
var users = require('users-management');
var players = users.addUser("pippo", "franco") // create one users
console.log(users.deleteUser(1)); // delete an user by id
console.log(users.getUserByID(1)); // return the user with the corrispondent ID
console.log(users.filteredByName("pippo")); // search user by name
users.reset(); // reset the users

```
