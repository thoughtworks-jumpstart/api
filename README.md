# API

💁‍♀️ A simple API service powered by [My JSON Server](https://my-json-server.typicode.com/)

## Available resources

GET [/fruits](https://my-json-server.typicode.com/thoughtworks-jumpstart/api/pokemon) - get all fruits

GET [/pokemon](https://my-json-server.typicode.com/thoughtworks-jumpstart/api/pokemon) - get all Pokémon

GET [/pokemon/1](https://my-json-server.typicode.com/thoughtworks-jumpstart/api/pokemon/1) - get a Pokémon with `id`

## Create a new resource

To create a new resource simply add a new property to `db.json`. See example [here](https://github.com/typicode/demo/blob/master/db.json).

```json
{
  "posts": [
    { "id": 1, "title": "Post 1" },
    { "id": 2, "title": "Post 2" },
    { "id": 3, "title": "Post 3" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 },
    { "id": 2, "body": "some comment", "postId": 1 }
  ]
}
```

This creates two resources posts and comments and these endpoints

- GET `/posts` - gets all posts
- GET `/posts/1` - gets one post with `id`
- GET `/comments` - gets all comments
- GET `/comments/1` - gets one comment with `id`
- GET `/posts/1/comments` - gets all comments belonging to a post

## List of public APIs

You may want to check these out for public APIs

- [toddmotto/public-apis](https://github.com/toddmotto/public-apis)
- [AnyAPI](https://any-api.com/)
- [API Directory - ProgrammableWeb](https://www.programmableweb.com/apis/directory)

## Caveat emptor

☝️ This API service is used for training and teaching purposes only. It is not meant to be used for production apps.
