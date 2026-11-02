# Repository location and public support

**GitHub remains the canonical, public home of this repository.** The official support link and Git source are:

https://github.com/HappyPilot/Computer_Connector_Support

For support requests, continue to use this GitHub repository and its existing public channels. Do not send users to a private infrastructure server.

## Internal archive

A private, pull-only Forgejo mirror is maintained for disaster recovery and source-history preservation. It does not replace GitHub, accept project contributions, or act as an independent public support endpoint.

For maintainers and automated development agents:

- Treat GitHub as the **only canonical write target**. Never force-push a recovered archive over this public repository.
- Before repository work, consult the machine-local Home Lab routing registry using `homelab-repo Computer_Connector_Support`. The expected status is `GITHUB_PRIMARY_NOT_MIGRATED`.
- An internal mirror must only pull changes from GitHub. Do not configure a push mirror back to GitHub or automatically rewrite existing Git remotes.
- Preserve existing working folders, branches, untracked changes, stashes and published support links.
- If the public project is ever formally relocated, update this file and the main README, verify the new endpoint and announce the change to users before retiring the old location.

No private NAS hostname, credentials, tokens or internal recovery paths are published here.
