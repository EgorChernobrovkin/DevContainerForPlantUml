# DevContainer for PlantUML

This repository provides a Dev Containers configuration for working with PlantUML. The files in the `src` folder are all you need to set up a devcontainer for PlantUML.

## Features

- Preconfigured environment for PlantUML (uses PlantUML extension: https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

## Requirements

- Docker
- Visual Studio Code with Dev Containers extension (https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## Getting Started

To use these files, follow these steps:

1. Create a folder named `.devcontainer` in the directory where you plan to work with PlantUML.
2. Copy all files from the `src` folder of this repository into the `.devcontainer` folder you just created.

## Usage

1. Open your project folder in Visual Studio Code.
2. If the Remote - Containers extension is installed, you should see a prompt to reopen the folder in the container. Click "Reopen in Container".
3. Once the container is built and running, you can start working with PlantUML.

## License

This project is licensed under the MIT License.