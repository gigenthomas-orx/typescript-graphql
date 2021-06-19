# Integrating Typscript with Graphql using Type-Graphl, a modern framework for building Graphql Node JS APIs

### To compile the application, run `npm run build-ts`

### To start the server, run `npm start`

## Dependencies

 - Typgoose, `@typegoose/typegoose`  A library for defining Mongoose models using TypeScript classes.
 - Type-Graphl, A library for creating GraphQL schema and resolvers with TypeScript, using `classes` and `decorators magic` :)!
 - Apollo-server-express, `apollo-server-express`, A library for quickly bootstrapping graphql servers with Apollo and Express
  

  ### For a note on other dependencies, please have a look at the `package.json` file. 


  Note: Run `npm install` to install all the projects dependencies...
  
  
##  Mutations
  
  mutation { createCategory(data : {name: "T Shirt",description:"This is a t shirt" }) { name, description, id } }
  
  
## Queries  
  query {
  returnSingleCategory( id: "60cd7bc5e11049e22c1f6aea")
   {
    name,
    description,
    id
  }
}

