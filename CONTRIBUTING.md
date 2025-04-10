# Contributing to Scientist-Py

We welcome contributions to improve the Scientist-Py library! Follow these steps to contribute:

## 1. Fork the Repository

Click the "Fork" button on the [GitHub repository page](https://github.com/yourusername/scientist-py) to create your copy of the project.

## 2. Clone Your Fork

Clone your fork to your local machine:

```bash
git clone https://github.com/yourusername/scientist-py.git
cd scientist-py
```

## 3. Install Dependencies

Make sure you have the necessary dependencies installed for development. From the project root, install the requirements:

```bash
pip install -r requirements.txt
```

For editable installs (e.g., for testing changes in real-time), run:

```bash
pip install -e .
```

## 4. Create a New Branch

Create a new branch for your changes. It's best practice to give your branch a meaningful name:

```bash
git checkout -b feature/your-feature-name
```

## 5. Make Changes

Make your changes to the codebase. Be sure to add tests in `tests/` that validate your changes.

## 6. Run Tests

Before committing your changes, ensure that all tests pass:

```bash
pytest
```

## 7. Commit and Push Your Changes

Once you're happy with your changes, commit and push them to your fork:

```bash
git add .
git commit -m "Your commit message"
git push origin feature/your-feature-name
```

## 8. Open a Pull Request

Go to the original repository's Pull Requests tab, and open a new pull request from your fork's branch. Provide a clear description of the changes you made.

## 9. Review and Merge

Once your pull request is reviewed and approved, it will be merged into the main repository.

Thank you for contributing! 🎉