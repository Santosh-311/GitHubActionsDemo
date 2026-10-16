# GitHubActionsDemo

A small Python project demonstrating unit testing with pytest and Continuous Integration using GitHub Actions.

## Run locally on Windows

If `python` is not recognized, install Python from https://www.python.org/downloads/windows/ and select **Add Python to PATH** during installation. Close and reopen Command Prompt after installation.

Then, from this folder, run:

```cmd
py --version
py -m pip install pytest
py main.py
py -m pytest -v
```

If `py` is not recognized but `python` works, replace `py` with `python`.

## GitHub Actions

1. Create a new empty GitHub repository named `GitHubActionsDemo`.
2. Open Command Prompt in this folder.
3. Run the following commands, replacing YOUR-USERNAME with your GitHub username:

```cmd
git init
git add .
git commit -m "Add GitHub Actions CI demo"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/GitHubActionsDemo.git
git push -u origin main
```

4. On GitHub, open the repository and select **Actions**.
5. Open the **Python Tests** workflow and inspect the latest run. A green tick means the tests passed.

If Git asks you to configure your identity, run:
```cmd
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
Use your own name and email address.
