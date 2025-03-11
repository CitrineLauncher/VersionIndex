# Bedrock

This folder contains the index for Bedrock Edition.


## Overview

Within this index, you'll find two main sections:

- **Versions:** A list of Bedrock Edition versions.
- **Dependencies:** A list of required dependencies.

## Data Structure

### Versions
Each entry in the **Versions** section includes:
- **Version:** The version string.
- **Type:** The release type; either `"Preview"` or `"Release"`.
- **UpdateIds:** Identifiers that the launcher uses to fetch the correct download, specified individually for:
  - **x64:** 64-bit processors.
  - **x86:** 32-bit processors.

### Dependencies
Each entry in the **Dependencies** section includes:
- **Name:** The name of the dependency.
- **Version:** The version of the dependency.
- **UpdateIds:** Identifiers that the launcher uses to fetch the correct download, specified individually for:
  - **x64:** 64-bit processors.
  - **x86:** 32-bit processors.