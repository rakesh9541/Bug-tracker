# Bug-tracker

Tech Stack:React.js, Node.js, PostgreSQL, Rest API, Prism


Sync prisma schema with your db:

```bash
# Run Migrations
cd apps/api && yarn prisma migrate dev

# Make a new migration
cd apps/api && yarn prisma migrate dev --name name_of_migration
```

To get started, run the following commands in the root directory:
```bash
# Installs all dependencies of the workspaces
yarn

# Starts the api dev server
yarn dev:api

# Starts the react dev server
yarn dev:frontend
```
