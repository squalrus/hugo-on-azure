# Hugo blog + Azure Template

## Getting started with Hugo

- Quick start: https://gohugo.io/getting-started/quick-start/
- Pick a theme: https://themes.gohugo.io/

Build locally with `hugo` ([docs](https://gohugo.io/commands/hugo/)) and run local server with `hugo server` ([docs](https://gohugo.io/commands/hugo_server/)).

Create a new post from the blog (or default) achetype with `hugo new blog/new-post.md`.

## Getting started with Azure

- "Tutorial: Publish a Hugo site to Azure Static Web Apps Preview": https://docs.microsoft.com/en-us/azure/static-web-apps/publish-hugo
- "Configure Azure Static Web Apps": https://docs.microsoft.com/en-us/azure/static-web-apps/configuration

Configuration for Azure Static Web Apps is defined in the `staticwebapp.config.json` file, which controls the following settings:

- Routing
- Authentication
- Authorization
- Fallback rules
- HTTP response overrides
- Global HTTP header definitions
- Custom MIME types

Current `content-security-policy` supports dependencies for:

- Google Analytics (need to account for code snippet on page with hash)
- Embedded Tweets
- Embedded Gists
