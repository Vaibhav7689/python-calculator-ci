# Python Calculator with CI/CD and GitHub Pages

A simple calculator implementation with automated testing using GitHub Actions and documentation hosted on GitHub Pages.

## Features
- Basic arithmetic operations (add, subtract, multiply, divide)
- Automated testing with pytest
- CI/CD pipeline with GitHub Actions
- Interactive calculator demo on GitHub Pages

## Project Structure
- `calculator.py`: Contains the calculator functions
- `tests/`: Contains pytest test cases
- `docs/`: Contains the GitHub Pages website
- `.github/workflows/`: Contains the CI/CD configuration

## GitHub Actions Workflow
This project uses GitHub Actions for:
1. Running tests on every push and pull request
2. Deploying the docs folder to GitHub Pages when tests pass

## GitHub Pages
Visit the project website at: https://your-username.github.io/python-calculator-ci/

## Local Development
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run tests: `pytest`