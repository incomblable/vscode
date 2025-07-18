# VSCode / VSCodium settings

Personal VSCode and VSCodium settings synchronized via the Sync Settings extension with Git backend. This is a personal configuration repository. Fork and modify settings to match your preferences before using.

## Setup

### Prerequisites

- Sync Settings extension installed

### Installation

1. Open the command palette and select `Sync Settings: Open the repository settings`.
1. Edit and paste the following configuration (comment the `dummy` part):

```yaml
# sync on remote git
repository:
  type: git
  # url of the remote git repository to sync with, required
  url: git@github.com:incomblable/vscode.git
  # branch to sync on, optional (set to `master` by default)
  branch: main
  # how to personalize the commit messages at https://github.com/zokugun/vscode-sync-settings/blob/master/docs/commit-messages.md
```

3. Open the command palette and select `Sync Settings: Download (repository -> user)`. The extension will apply the user settings and request to restart the application. Say yes, then, re-do this step in order to install the extensions.
