# TypeGrpahQL Back-end Server
(Front-End Coming Soon...)

## Steps to run locally:
1. Clone this repo.
1. Run **yarn install**
1. Create .env file:
    - Add variable: ORIGIN ("http://localhost:3000") & SECRET ("Any string)
1. Start PostgreSQL
    - Create tables: typegraphql-example, typegraphql-example-test
1. Start Redis Server
1. Run **yarn test**
1. Run **yarn start**

## Server Featurs:
- TypeGraphQL Setup
- Register User Resolver
- Validation TypeGraphQL
- Login User
- Authorization TypeGraphQL
- **Confirmation Email using *nodemailer***
- Forgot Password
- Logout User
- **Setting up a Test Environment**
- Testing Resolvers
- **Higher Order Resolvers**
- **File Uploads**
- **Query Complexity**