# Contributing Guide

Thank you for wanting to help! This guide walks you through making your **first pull request (PR)**. Don't worry about getting it perfect — that's what reviews are for.

## The workflow at a glance

```
Fork → Clone → Branch → Change → Commit → Push → Pull Request
```

## Step by step

### 1. Fork and clone
Click **Fork** on GitHub, then:

```bash
git clone https://github.com/YOUR-USERNAME/html-css-beginners.git
cd html-css-beginners
```

### 2. Connect to the original repo (do this once)
This lets you pull in updates from class.

```bash
git remote add upstream https://github.com/codewithaddo/html-css-beginners.git
```

### 3. Get the latest changes before you start

```bash
git checkout main
git pull upstream main
```

### 4. Create a branch for your change
Name it after what you're doing:

```bash
git checkout -b fix-forms-label
```

### 5. Make your change
Edit the file(s), save, and **open the page in your browser to check it still works**.

### 6. Commit

```bash
git add .
git commit -m "Fix label 'for' attribute in forms.html"
```

Good commit messages are short and say *what* changed: `Add table caption to simpleTables.html`, not `update`.

### 7. Push to your fork

```bash
git push origin fix-forms-label
```

### 8. Open a pull request
Go to your fork on GitHub → click **Compare & pull request** → describe what you changed and why → **Create pull request**.

The instructor will review it. If changes are requested, just make them on the same branch, commit and push again — the PR updates automatically.

## Rules of the house

- ✅ One change (one idea) per pull request
- ✅ Test your page in a browser before you push
- ✅ Keep code indented and readable — beginners will read it
- ✅ Personal exercise work goes in `students/your-github-username/` only
- ❌ Don't edit another student's folder
- ❌ Don't push directly to `main`

## Need help?
Open an issue and ask — there are no silly questions here. Please also read our [Code of Conduct](CODE_OF_CONDUCT.md).
