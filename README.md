# Ex Echo Bot
Ex Echo Bot is an example of a facebook messenger bot that echos whats sent to it.

# Usage

To start your Phoenix app:

  1. Install dependencies with `mix deps.get`
  2. Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  3. Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

# Configurations
When starting it in production, you need to set the following environment varibles

`VERIFY_TOKEN` the facebook verification token that will be sent in the facebook challenge.
`PAGE_TOKEN` the facebook page token you will use with your app.

To get the `VERIFY_TOKEN` and `PAGE_TOKEN` follow the instructions [here ](https://developers.facebook.com/docs/messenger-platform/quickstart)

This project uses [EXFacebook-Messenger](https://github.com/oarrabi/EXFacebook-Messenger) as a dependency to create the chat bot.

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
