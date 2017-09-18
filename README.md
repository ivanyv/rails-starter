## Rails Starter Template

### Getting Started

1. Clone/fork this repo
2. `bundle install`
3. `rake app:rename[YourAppName]`
4. (optional) Re-initialize git (`rm -rf .git && git init .`)
5. Run `overcommit --install && overcommit --sign`

### Configuration

Everything is configured using environment variables so we have it all on one place.

- `.env` contains all the variables used by the application.
- `.env.development` houses settings that can be shared between developers.
- `.env.test` contains settings for the test environment
- `.env.production` this file belongs on the server; we set here all the variables (or use Heroku's variables)
- `.env.local` is ".gitignore'd" so each dev can override any setting

### Database

Using PostgreSQL via a `DATABASE_URL` environment variable.

### Asset Management

Using bower at `vendor/assets/components`.
