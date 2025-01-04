## Contributing to the Collaboro-AI-Foundation SIP Gateway (gateway)

We welcome contributions from the community! This document outlines how you can contribute to the project, including reporting issues, suggesting improvements, and submitting pull requests.

**Getting Started**

1.  **Fork the repository:** Create a fork of the `Collaboro-AI-Foundation/gateway` repository on GitHub.
2.  **Clone your fork:** Clone your forked repository to your local machine using `git clone https://github.com/<your_username>/gateway.git`. Replace `<your_username>` with your GitHub username.
3.  **Set up a development environment:** Ensure you have a working Go development environment (version 1.x or higher) installed. You can download Go from [https://go.dev/dl/](https://go.dev/dl/).

**Reporting Issues**

*   Before creating a new issue, check the existing issues list to see if a similar issue has already been reported. You can find the issues list on the project's GitHub page.
*   If you find a new issue, please provide a clear and concise description of the problem. Include details such as:
    *   Steps to reproduce the issue
    *   Expected behavior vs. actual behavior
    *   Any relevant error messages or logs
    *   Your Go version (run `go version`) and operating system

**Submitting Pull Requests**

1.  **Create a new branch:** Create a new branch on your local fork for your changes: `git checkout -b feature/your-feature-name` (or `bugfix/issue-number` for bug fixes).
2.  **Make changes and commit:** Make your changes to the codebase and commit them with descriptive commit messages: `git commit -m "Add a descriptive commit message"`. Follow the conventional commits specification if possible.
3.  **Write unit tests:** **Unit tests are mandatory for all code contributions.** Ensure that your changes are covered by appropriate unit tests. Place tests in `*_test.go` files in the same package as the code they are testing.
4.  **Run tests:** Run all tests to ensure they pass: `go test ./...`.
5.  **Push your changes:** Push your changes to your forked repository on GitHub: `git push origin feature/your-feature-name`.
6.  **Create a pull request:** Create a pull request from your branch to the `main` branch of the upstream `Collaboro-AI-Foundation/gateway` repository.

**Code Style and Formatting**

*   We follow standard Go conventions for code formatting and style.
*   Use `go fmt` to format your code: `go fmt ./...`

**License**

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

**Communication**

For general discussions, questions, or suggestions, please open an issue on the project's GitHub page.

**We appreciate your contributions to the Collaboro-AI-Foundation SIP Gateway project!**
