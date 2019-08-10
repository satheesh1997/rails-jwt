# rails-jwt

This is a simple rails api that uses jwt token for authentication

urls present:
  1. POST /auth/login/ -> authenticates the user and displays the token
  2. GET /users/ -> lists all the users
  3. POST /users/ -> create a new user
  4. PUT /users/{username} -> updates a user
  5. DELETE /users/{usernmae} -> deletes the particular user
  6. GET /users/{username} -> shows the details of the particular user
  

Note:
  This webapp is developed while trying to explore how to build a auth
 system for rest-api in rails.
