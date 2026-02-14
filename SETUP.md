# Create the GitHub repo and publish

The **Mafia-Site** folder is ready. Create the repo on GitHub (public), then push.

## 1. Create the repo on GitHub

1. Go to **https://github.com/new**
2. **Repository name:** `Mafia-Site`
3. **Description:** (optional) e.g. `Privacy & Terms site for Mafia app`
4. Choose **Public**
5. **Do not** add a README, .gitignore, or license (this folder already has them)
6. Click **Create repository**

## 2. Push from your machine

In a terminal, from the **Mafia-Site** folder:

```bash
cd /Users/vagh/Cursor/Mafia-Site
git remote add origin https://github.com/vaghblogger/Mafia-Site.git
git branch -M main
git push -u origin main
```

(If you use a different GitHub username, replace `vaghblogger` in the URL.)

## 3. Turn on GitHub Pages

1. On GitHub, open the **Mafia-Site** repo
2. **Settings** → **Pages**
3. Under **Source**, choose **Deploy from a branch**
4. **Branch:** `main` → **Folder:** `/ (root)` → **Save**
5. After a minute, the site will be at: **https://vaghblogger.github.io/Mafia-Site/**

Use these URLs in Play Console and App Store Connect:

- **Privacy:** https://vaghblogger.github.io/Mafia-Site/privacy.html  
- **Terms:** https://vaghblogger.github.io/Mafia-Site/terms.html  
