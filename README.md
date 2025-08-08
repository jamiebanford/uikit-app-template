# UIKit App Template

A minimal Xcode project template for starting iOS apps with UIKit without storyboards.

## Features

- ✅ Pure UIKit implementation (no storyboards)
- ✅ Default scene configuration set in the App Delegate
- ✅ A root view controller set in the Scene Delegate
- ✅ A placeholder launch screen image
- ✅ Bundle identifier and development team set via an Xcode configuration settings file

## Getting started

### 1. Clone the Repository

```bash
git clone https://github.com/jamiebanford/uikit-app-template.git
cd uikit-app-template
```

### 2. Configure the Project

Create an [Xcode configurations settings file](https://developer.apple.com/documentation/xcode/adding-a-build-configuration-file-to-your-project/) named `Project.xcconfig` in the project root with your bundle identifier and development team:

```
PRODUCT_BUNDLE_IDENTIFIER = your.bundle.id
DEVELOPMENT_TEAM = YOUR_TEAM_ID
```

### 3. Use the Template

This repository is set up as a GitHub template. To [create a new project based on this template](https://github.blog/developer-skills/github/generate-new-repositories-with-repository-templates/), click the "Use this template" button at the top of the repository page, then create your new repository.

## Contributing

If you think something is missing or broken please feel free to create an issue or open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
