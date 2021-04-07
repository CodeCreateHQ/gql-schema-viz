# gql-schema-viz
Visualize your graphql schema


## Relevant Research

[Video Link](https://www.youtube.com/watch?v=IqtYr6RX32Q)

[GraphQL-JS Internals Article Link](https://www.apollographql.com/blog/graphql-js-the-hidden-features-effaca7a81b3/)

[Direct Link](https://graphql.org/swapi-graphql/?query=%7B%0A%20%20__schema%7B%0A%20%20%09types%20%7B%0A%20%20%20%20%20%20name%0A%20%20%20%20%09fields%20%7B%0A%20%20%20%20%20%20%20%20name%0A%20%20%20%20%20%20%20%20__typename%0A%20%20%20%20%20%20%20%20type%20%7B%0A%20%20%20%20%20%20%20%20%20%20name%0A%20%20%20%20%20%20%20%20%20%20ofType%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20name%0A%20%20%20%20%20%20%20%20%20%20%20%20description%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%20%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D)

```
{
  __schema {
    types {
      name
      fields {
        name
        __typename
        type {
          name
          ofType {
            name
            description
          }
        }
      }
    }
  }
}
```
