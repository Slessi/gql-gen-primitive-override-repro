# Repro steps

With yarn

```sh
yarn
yarn gql-gen --schema schema.graphql --template graphql-codegen-typescript-template --out ./types.ts
cat types.ts
```

With npm & npx (>= 5.2)

```sh
npm i
npx gql-gen --schema schema.graphql --template graphql-codegen-typescript-template --out ./types.ts
cat types.ts
```
