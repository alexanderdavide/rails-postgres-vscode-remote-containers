# Rails Postgres Remote Containers

## Prerequisites

1. Install [VSCode](https://code.visualstudio.com/)
2. Install the VSCode [Remote Development plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
3. Install [Docker](https://www.docker.com) and [Docker Compose](https://docs.docker.com/compose/)

## Starting

1. Clone this repository
2. Open the folder in VSCode
3. Execute 'Remote-Containers: Reopen in Container' from the VSCode command palette
4. VSCode automatically downloads the dependencies and starts up the stack. The rails app is available on http://localhost:3000.
5. You will be left with a VSCode window to develop in. Every integrated terminal is running inside the rails container.

## Shutdown

Simply close VSCode.
