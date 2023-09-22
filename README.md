# AzureNamingTool - Docker

![Docker pulls](https://img.shields.io/docker/pulls/tfisicaro/aznamingtool.svg)

> The Azure Naming Tool is a .NET 7 Blazor application, with a RESTful API. The UI consists of several pages to allow the configuration and generation of Azure Resource names. The API provides a programmatic interface for the functionality.

This repository only contains a GitHub Actions workflow to daily build Microsoft's own provided Dockerfile from their source code in the [mspnp GitHub organization](https://github.com/mspnp). The image is scheduled to be build and pushed to my own [Docker repository](https://hub.docker.com/repository/docker/tfisicaro/aznamingtool) as you can see in the GitHub Actions workflow

## License

This project is licensed under the MIT License. See license in [LICENSE.md](./LICENSE.md) or [view the license](https://raw.githubusercontent.com/mspnp/AzureNamingTool/main/LICENSE) in the source repository.
