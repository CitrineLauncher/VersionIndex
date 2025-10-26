# Bedrock

This directory contains the index for Bedrock Edition.

---

## GamePackages.json

This file contains available client builds and their dependencies.

### Structure

#### BaseUrls

Lists base URLs where package files are hosted.


#### Packages

Each package entry includes:

| Field            | Description                                                             |
| ---------------- | ----------------------------------------------------------------------- |
| **Version**      | The build version.                                                      |
| **BuildType**    | Either `"Release"` or `"Preview"`.                                      |
| **Platform**     | Either `"WindowsUWP"` or `"WindowsGDK"`.                                |
| **Architecture** | CPU architecture of the package.                                        |
| **UpdateId**     | Unique ID used to retrieve this build.                                  |
| **Path**         | Relative URI to the game package (only for `"Platform": "WindowsGDK"`). |


#### Dependencies

Each dependency entry includes:

| Field                 | Description                                             |
| --------------------- | ------------------------------------------------------- |
| **PackageFamilyName** | The package family name of the dependency.              |
| **Version**           | The dependency version.                                 |
| **Architecture**      | CPU architecture of the dependency.                     |
| **UpdateId**          | The identifier used to retrieve the dependency package. |

---


## ServerPackages.json

This file contains available server builds.

### Structure

#### BaseUrls

Lists the base URLs for each platform and release channel.


#### Packages

Each package entry includes:

| Field         | Description                                                                               |
| ------------- | ----------------------------------------------------------------------------------------- |
| **Version**   | The build version.                                                                        |
| **BuildType** | Either `"Release"`, `"Beta"` or `"Preview"`.                                              |
| **Path**      | The filename of the downloadable server archive.                                          |
