# Status

Uptime monitor and status page built from the [Upptime](https://github.com/upptime/upptime) template.

Monitors the services on pontiff.de.

## Add a site

1. Add sites under `sites:` in `.upptimerc.yml`.
2. Make sure the repository secret `GH_PAT` holds a valid fine-grained token
   (Contents, Actions, Issues, Workflows: read and write on this repository).
3. Push. **Setup CI** runs on its own when `.upptimerc.yml` changes.

Only `.upptimerc.yml` should be edited. Everything in `.github/workflows/` is
generated and overwritten by the template update.
