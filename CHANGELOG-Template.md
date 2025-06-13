# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2024-03-09

### Added

- **Assets** - Folder to maintain assets for the presentation that will be kept only in the private repository.
- **Assets\README.md** - Markdown file used to create the Assets folder; should be deleted once an asset is added to the folder.
- **EventMaterials** - Folder to store the finished event materials. This folder will be synchronized with the public repository.
- **EventMaterials\README.md** - Directory of the events material folder.
- **CHANGELOG-Template.md** - This file; tracks the changes to the template.
- **CHANGELOG.md** - Change log of changes to the presentation.
- **LICENSCE.md** - Contains details about the license for the public folder.

### Changed

- **Presentations** - Folder repurposed to store the original presentation files. This folder will not be synchronized with thee public folder.
- **Presentations\Presentation.pptx** - Template PowerPoint for the presentation.
- **README.md** - Adding the Resources section to include resources attendees can use to learn more about the presentation's topic.

### Removed

-- **Presentation.pptx** - Moved to the *Presentations* folder.

## [1.0.0] - 2023-11-01

### Added

- **Demos\** - Folder to store demos for the presentation.
- **Demos\Readme.md - Readme file in order to create the *Demos* folder; could be updated to include information about the included demos or just be deleted after adding the demo files.
- **Presentations** - Contains the event materials delivered presentations.
- **Presentations\Readme.md** - Readme file in order to create the *Presentations* folder; should be deleted after adding presentation material to the folder.
- **Resources** - Contains the resources for the presentation.
- **Resources\Readme.md** - Readme file in order to create the *Resources* folder; should be deleted after adding other files to the folder.
- **.gitignore** - Initial ignore file.
- **LICENSE** - Contains details about the license for the repository.
- **Presentation.pptx** - Template PowerPoint for the presentation.
- **README.md** - Contains summary information for the presentation.