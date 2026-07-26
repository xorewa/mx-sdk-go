# Disabled workflows

`create_release.yml` was removed from the active workflow directory because it creates GitHub releases using write credentials. Xorewa workflows are restricted to validation on the `NewArc` branch and must not publish release artifacts automatically.

Re-enable a release workflow only after an explicit Xorewa release policy, scoped credentials, and review are in place.
