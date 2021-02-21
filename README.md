## Requirements

The specifications have shifted slightly since the last developer meeting. Your client's budget recently increased and now they're able to pat for a database service. You've done your research and found that MongoDB is the most suitable database platform for the project. With this new information, the client has asked that you modify the API server to store all `Tank` related data to be stored in the database. The `Profile` data can be handled the same way as it was originally implemented, where the profile data is saved in a variable on the server. If you want to modify the `Profile` routes to save the data in the database as well, you may, but you don't have to (you won't get extra marks if you do and you won't lose marks if you don't).

You'll need to sign up on the MongoDB website, create a project and add a cluster to your project.

The following routes should be modified to support the use of the mongodb database.

```jsx
GET /data
POST /data
PATCH /data/:id
DELETE /data/:id
```
