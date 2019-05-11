# Getaways
## Absinthe-Phoenix GraphQL API application

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup && mix ecto.migrate`
  * Start Phoenix endpoint with `mix phx.server`
  * Now you can visit [`http://localhost:4000/graphiql `](http://localhost:4000/graphiql) from your browser.
  * Query list of places:
  ```
  query {
    places {
      id
      name
      location
    }
  }
  ```
  * Query a place with `id=2`
  ```
  query {
    place(id: 2) {
      id
      name
      location
      maxGuests
    }
  }
  ```

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
