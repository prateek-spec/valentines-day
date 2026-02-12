# 💖 Quick Reference - Push Changes to GitHub

## After Making Changes Locally

**Copy and paste this into PowerShell:**

```bash
cd "c:\Users\zopep\Downloads\Valentines" && git add . && git commit -m "Update Valentine's page" && git push
```

---

## What This Does

| Command | Action |
|---------|--------|
| `git add .` | Stage all changed files |
| `git commit -m "..."` | Save changes with a message |
| `git push` | Upload to GitHub |

---

## Live Site Link

🔗 **Share this with someone:**
```
https://prateek-spec.github.io/valentines-day/
```

Changes appear on the live site within **5-10 seconds** after pushing!

---

## Common Changes

### 🎨 Change colors, text, or layout
1. Edit `index.html` or `style.css`
2. Run the push command above
3. Refresh the live link

### 🖼️ Add/replace images
1. Add new images to the `gif/` folder
2. Update the image URL in `index.html`
3. Run the push command above

### ✨ Add/modify pages
1. Add new pages to `index.html`
2. Add styles to `style.css`
3. Run the push command above

---

## Troubleshooting

**"Nothing to commit"?**
- You haven't made any changes yet. Edit a file and try again.

**Push takes too long?**
- Normal — GitHub needs 5-10 seconds to deploy
- Go to Settings > Pages to check deployment status

**Changes don't appear on live site?**
- Hard refresh: `Ctrl+Shift+R` (clears cache)
- Wait 10 seconds and refresh again
