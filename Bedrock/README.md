# Bedrock

This folder contains the index for Bedrock Edition.


## Overview

Within this index, you'll find two main sections:

- **Versions:** A list of Bedrock Edition versions.
- **Dependencies:** A list of required dependencies.


## Index Structure

### Versions

Each entry in the **Versions** section includes:

- **Version:** The version string.
- **Channel:** The release channel, either `"Preview"` or `"Release"`.
- **Type:** The package type, either `"MSIXVC"` or `"APPX"`.
- **ServerFileName (optional):** The name of the dedicated server's download file, if available.
- **UpdateId:** The identifier which is used to retrieve the 64-bit build.
- **Path:**
  - For entries with `"Type": "MSIXVC"`, this field contains the relative URI to the package.
  - For `"Type": "APPX"`, this field is not present.

### Dependencies

Each entry in the **Dependencies** section includes:

- **Name:** The dependency name.
- **Version:** The dependency version.
- **UpdateId:** The identifier which is used to retrieve the 64-bit build.