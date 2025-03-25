# Minecraft Bedrock Behavior Pack Schema

A JSON schema for validating Minecraft Bedrock behavior pack manifest.json files.

## Usage

Add this schema to your VSCode workspace settings:

```json
{
    "json.schemas": [
        {
            "fileMatch": [
                "*.json"
            ],
            "url": "https://raw.githubusercontent.com/your-username/minecraft-bedrock-schema/main/manifest.json"
        }
    ]
}
```

## Features

- Validates all required fields
- Checks UUID formats
- Ensures correct version number formats
- Provides auto-completion
- Shows helpful descriptions for each property
