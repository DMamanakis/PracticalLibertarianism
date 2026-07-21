# GitHub Setup and First Push

This guide publishes this local folder to:

`https://github.com/DMamanakis/PracticalLibertarianism`

## 1. Authenticate `gh` (once per machine)

```bash
gh auth login
```

Choose:

- GitHub.com
- HTTPS
- Authenticate in browser

## 2. Initialize git in this folder

From the project root (`PracticalLibertarianism`):

```bash
git init
git add .
git commit -m "Initial repository import"
git branch -M main
```

## 3. Create or connect the GitHub repository

If the repo does **not** exist yet:

```bash
gh repo create DMamanakis/PracticalLibertarianism --public --source=. --remote=origin --push
```

If the repo already exists:

```bash
git remote add origin https://github.com/DMamanakis/PracticalLibertarianism.git
git push -u origin main
```

## 4. Verify

```bash
git remote -v
gh repo view DMamanakis/PracticalLibertarianism --web
```

## Ongoing Updates

```bash
git add .
git commit -m "Describe your update"
git push
```
