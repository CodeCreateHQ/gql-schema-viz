# gql-schema-viz
Visualize your graphql schema


## Relevant Research

```
{
  __schema{
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
