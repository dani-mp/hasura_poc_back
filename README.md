# Hasura POC (Hasura engine)

## Getting started
1. Install Docker locally.
1. Clone the repo.
1. Add .env file (ask a collaborator for the current env vars).
1. Run `docker-compose up -d` from the root folder.
1. Install hasura-cli: https://docs.hasura.io/1.0/graphql/manual/hasura-cli/install-hasura-cli.html.
1. Run `cd hasura && hasura console --admin-secret <secret>`.
1. Don't forget to push the changes made in Hasura dashboard.
