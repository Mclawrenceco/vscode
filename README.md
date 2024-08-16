# Visual Studio Code - Open Source ("Code - OSS")

[![Feature Requests](https://img.shields.io/github/issues/microsoft/vscode/feature-request.svg)](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc)
[![Bugs](https://img.shields.io/github/issues/microsoft/vscode/bug.svg)](https://github.com/microsoft/vscode/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3Abug)
[![Gitter](https://img.shields.io/badge/chat-on%20gitter-yellow.svg)](https://gitter.im/Microsoft/vscode)

## Repository Overview

This repository, **Code - OSS**, is where we (Microsoft) collaborate with the community to develop [Visual Studio Code](https://code.visualstudio.com). In addition to working on code and issues, we also publish our:

- [Roadmap](https://github.com/microsoft/vscode/wiki/Roadmap)
- [Monthly iteration plans](https://github.com/microsoft/vscode/wiki/Iteration-Plans)
- [Endgame plans](https://github.com/microsoft/vscode/wiki/Running-the-Endgame)

The source code is available under the standard [MIT license](https://github.com/microsoft/vscode/blob/main/LICENSE.txt).

## Visual Studio Code

<p align="center">
  <img alt="VS Code in action" src="https://user-images.githubusercontent.com/35271042/118224532-3842c400-b438-11eb-923d-a5f66fa6785a.png">
</p>

[Visual Studio Code](https://code.visualstudio.com) is a distribution of the `Code - OSS` repository with Microsoft-specific customizations, released under a traditional [Microsoft product license](https://code.visualstudio.com/License/).

VS Code combines the simplicity of a code editor with essential features for the core edit-build-debug cycle. It offers:

- Comprehensive code editing, navigation, and understanding
- Lightweight debugging
- A rich extensibility model
- Seamless integration with existing tools

VS Code is updated monthly with new features and bug fixes. You can download it for [Windows, macOS, and Linux](https://code.visualstudio.com/Download). For the latest daily updates, install the [Insiders build](https://code.visualstudio.com/insiders).

## Contributing

You can participate in this project in many ways:

- [Submit bugs and feature requests](https://github.com/microsoft/vscode/issues), and help us verify them
- Review [source code changes](https://github.com/microsoft/vscode/pulls)
- Review and contribute to the [documentation](https://github.com/microsoft/vscode-docs)

If you're interested in contributing directly to the code base, refer to our guide: [How to Contribute](https://github.com/microsoft/vscode/wiki/How-to-Contribute). Topics covered include:

- [Building and running from source](https://github.com/microsoft/vscode/wiki/How-to-Contribute)
- [Development workflow, including debugging and running tests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#debugging)
- [Coding guidelines](https://github.com/microsoft/vscode/wiki/Coding-Guidelines)
- [Submitting pull requests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#pull-requests)
- [Finding an issue to work on](https://github.com/microsoft/vscode/wiki/How-to-Contribute#where-to-contribute)
- [Contributing to translations](https://aka.ms/vscodeloc)

## Feedback

We value your feedback! You can:

- Ask a question on [Stack Overflow](https://stackoverflow.com/questions/tagged/vscode)
- [Request a new feature](CONTRIBUTING.md)
- Upvote [popular feature requests](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc)
- [File an issue](https://github.com/microsoft/vscode/issues)
- Connect with the extension author community on [GitHub Discussions](https://github.com/microsoft/vscode-discussions/discussions) or [Slack](https://aka.ms/vscode-dev-community)
- Follow [@code](https://twitter.com/code) on Twitter and let us know what you think!

For more feedback channels and community-driven options, visit our [wiki](https://github.com/microsoft/vscode/wiki/Feedback-Channels).

## Related Projects

Many core components and extensions for VS Code have their own repositories on GitHub. For example:

- [Node debug adapter](https://github.com/microsoft/vscode-node-debug)
- [Mono debug adapter](https://github.com/microsoft/vscode-mono-debug)

For a complete list, visit the [Related Projects](https://github.com/microsoft/vscode/wiki/Related-Projects) page on our [wiki](https://github.com/microsoft/vscode/wiki).

## Bundled Extensions

VS Code includes a set of built-in extensions located in the [extensions](extensions) folder, including grammars and snippets for many languages. Extensions that provide rich language support, such as code completion or Go to Definition, have the suffix `language-features`. For example:

- `json`: Provides coloring for `JSON`
- `json-language-features`: Provides rich language support for `JSON`

## Development Container

This repository includes a Visual Studio Code Dev Containers / GitHub Codespaces development container.

### Getting Started with Dev Containers

- For [Dev Containers](https://aka.ms/vscode-remote/download/containers), use the **Dev Containers: Clone Repository in Container Volume...** command to create a Docker volume for better disk I/O on macOS and Windows.
  - If you already have VS Code and Docker installed, click [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/microsoft/vscode) to get started. This will automatically install the Dev Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.

- For Codespaces, install the [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces) extension in VS Code, and use the **Codespaces: Create New Codespace** command.

> **Note:** The Docker / Codespace should have at least **4 Cores and 6 GB of RAM (8 GB recommended)** to run a full build. See the [development container README](.devcontainer/README.md) for more details.

## Code of Conduct

This project follows the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any questions or comments.

## License

Licensed under the [MIT](LICENSE.txt) license.

---

### Suggested Enhancements:

1. Table of Contents: Add a table of contents to make navigation easier, especially for longer documents.
2. Installation Guide: Consider adding a section that guides users through setting up their development environment.
3. Contributing Guidelines: Include more detailed instructions or a link to a separate `CONTRIBUTING.md` file for new contributors.
4. FAQs: Add a Frequently Asked Questions section to address common queries.
5. Issue Templates: Mention the use of issue templates to help users file bugs or feature requests more effectively.
