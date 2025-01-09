# Montør App Resources

This repository contains resources needed for Montør to function

## Version Configuration

This file, `app-version.json`, contains configuration information for the auto update feature. Below is a description of each field in the JSON file:

### Fields

- `latest_version`: The latest version of the application. This is the version that users should ideally be using.
- `supported_version`: The minimum version of the application that is supported. Users with versions below this will need to update.
- `force_update`: A boolean value indicating whether users should be forced to update to the latest version.
- `available_version`: A list of all available versions of the application.
