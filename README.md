# Blazor RichTextEditor - Image upload

This sample explains about how to use the controller action with Blazor Rich Text Editor (Blazor Server App) to upload and save an image in the required destination.

## Project Overview

This sample shows how to integrate image upload functionality into the Blazor Rich Text Editor in a Blazor Server application. It demonstrates using a server-side controller action to receive image files from the editor, save them to a destination on disk or configured storage location, and make the saved images available for insertion in editor content.

## Key Features

- Server-side image upload handler using a controller action
- Integration with Blazor Rich Text Editor for image insertion
- Guidance for opening, building, and running the sample in Visual Studio

## Prerequisites

- Visual Studio 2022
- .NET SDK matching the project in the solution (install via Visual Studio installer)

## Setup & Running Steps

Installation

```bash
git clone https://github.com/SyncfusionExamples/blazor-richtexteditor-image-upload.git
cd blazor-richtexteditor-image-upload
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## Usage

Open the Rich Text Editor page in the running app, use the image insert/upload feature, and follow prompts to select an image. The editor will post the file to the server controller action, which saves it to the configured destination and returns a URL usable by the editor to display the image in content.

## Troubleshooting

- Ensure NuGet packages are restored and the project builds successfully before running.

## License & Support

This sample is provided for demonstration purposes. For setup questions, use the project documentation.

>Looking for the full Blazor Rich Text Editor component overview, features, pricing, and documentation? Visit the [Blazor Rich Text Editor](https://www.syncfusion.com/blazor-components/blazor-rich-text-editor) page.
