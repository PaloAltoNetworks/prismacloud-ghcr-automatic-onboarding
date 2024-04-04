# GitHub Container Registry List

This Python application lists the GitHub Container Registries (GHCR) for a specified GitHub organization. It utilizes the GitHub API to fetch registry details and supports limiting the number of registries returned. Additionally, it offers a debug logging feature for more detailed output during execution.

## Features

- Fetch GHCR details for a specific GitHub organization.
- Can limit the number of registries returned.
- Onboard GHCR registries to Prisma Cloud
- Debug logging for troubleshooting and development purposes.

## Prerequisites

Before running this application, ensure you have the following:

- Python 3.9 or higher installed.
- A GitHub Personal Access Token with permissions to access the organization's packages.
- The `dotenv` library if you're using environment variables to manage your GitHub token and other configurations.

## Usage

Run the script from the command line, providing the necessary arguments:

```sh
python main.py -o <OrganizationName> -t <GHCRTokenName> -l <Limit> --debug
```

