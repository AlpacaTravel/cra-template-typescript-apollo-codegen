# Create React App Template

This template is for use with Create React App. It add in typescript and GraphQL
using Apollo and codegeneration for a type-safe development environment.

The following template configuration includes;

- Typescript
- Styled Components
- Apollo Client
- GraphQL
- GraphQL Codegen

## Getting Started

Install react via the recommended method:

```
npx create-react-app my-app --template="@alpaca-travel/typescript-apollo-codegen"
```

Once your react application is created, create an .env.local with updated
settings for your project, including the Alpaca Travel API Keys.

```
REACT_APP_GRAPHQL_ACCESS_TOKEN=pk/sk...
```

## Using GraphQL

Create a folder `src/graphql` and write your GraphQL documents there. You
can run the code-generation from the script `yarn graphql-codegen`.

The codegen is configured to output the Typescript types to
`src/graphql/types.ts` and also create corresponding Apollo Hooks for your
Application.
