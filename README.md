# This project was created using `create-beth-app`
## To open an issue: https://github.com/ethanniser/the-beth-stack
## To discuss: https://discord.gg/Z3yUtMfkwa

### To run:

1. `bun install`
2. create a new turso database with `turso db create <name>`
3. get the database url with `turso db show --url <name>`
4. get the auth token with `turso db tokens create <name>`
5. (optional) create a new github developer app and get credentials
6. copy `.env.example` to `.env`
7. fill out all enviorment variables (refer to the config file to see schema)
8. `bun db:push`
9. `bun dev`

