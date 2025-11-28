Professional profile setup on Windows (cmd)

1) Create the special profile repo (must match your username exactly):

```cmd
REM Replace Aayush9808 if your username differs
mkdir Aayush9808 && cd Aayush9808
git init
echo # placeholder> README.md
git add README.md
git commit -m "chore: init profile repo"
git branch -M main
git remote add origin https://github.com/Aayush9808/Aayush9808.git
git push -u origin main
```

2) Replace the placeholder with the curated profile README in this folder:

```cmd
cd /d c:\Users\aayus\OneDrive\Pictures\Desktop\Github_profile
git init
git add README.md CHECKLIST.md CONTRIBUTING.md SECURITY.md LICENSE TEMPLATES ENHANCEMENTS.md
git commit -m "feat(profile): add professional profile README and templates"
git branch -M main
git remote add origin https://github.com/Aayush9808/Aayush9808.git
git push -u origin main
```

Notes
- You’ll be prompted to authenticate with GitHub when pushing.
- Keep this repo public so the README appears on your profile.
- Optional: use the GitHub Desktop app or the `gh` CLI if preferred.
