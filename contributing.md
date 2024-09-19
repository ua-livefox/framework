# Contributing to [LiveCMS]

We welcome contributions to improve this project! Below is a guide on how you can get involved and contribute effectively.

## Table of Contents

1. [How to Contribute](#how-to-contribute)
2. [Reporting Bugs](#reporting-bugs)
3. [Suggesting Features](#suggesting-features)
4. [Creating Pull Requests](#creating-pull-requests)
5. [Code Style](#code-style)
6. [Local Development](#local-development)

---

## How to Contribute

1. **Fork the repository.**
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/my-new-feature
   ```
3. **Commit your changes** to your branch:
   ```bash
   git commit -m "Add feature: description of the feature"
   ```
4. **Push the changes** to your fork:
   ```bash
   git push origin feature/my-new-feature
   ```
5. **Open a pull request** on the original repository.

---

## Reporting Bugs

If you encounter a bug, please report it by creating an issue on GitHub. Include:

- A clear and descriptive title.
- Steps to reproduce the issue.
- Expected behavior.
- Any relevant error messages or screenshots.

---

## Suggesting Features

To suggest a new feature or improvement, create an issue describing:

- The problem it solves or the functionality it adds.
- Why it would be beneficial to the project.

---

## Creating Pull Requests

When submitting a pull request:

- Ensure your code is well-documented.
- Write or update relevant tests.
- Verify that your changes do not break existing functionality.
- Provide a clear and descriptive title.
- Include a detailed description of your changes.

---

## Code Style

To maintain consistency, follow these guidelines:

- Follow [PSR-12](https://www.php-fig.org/psr/psr-12/) coding standards for PHP.
- Use clear and meaningful variable, method, and class names.
- Ensure proper indentation (spaces, not tabs).
- Keep functions short and focused on a single task.

---

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/php-livecms/framework.git
   ```
2. Install dependencies:
   - **exec()** enabled — required for remote connections with programs like FFmpeg for video processing.
   - **file_put_contents()** enabled — used for writing data to files, such as system .ini files.
   - **file_get_contents()** enabled — used for reading file content as a string.
   - **ZipArchive** class enabled — used for installing new components via the installer.
   - **PHP version**: 8.3.6 — for interacting with PHP scripts.
   - **MySQL version**: 5.7.44 (supports versions 5.5/5.6/5.7) — database.
   - **PDO driver**: enabled — for working with MySQL databases.
3. Make changes and run tests to ensure everything works properly.

---

Thank you for contributing to [LiveCMS]!

---
