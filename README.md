# GEDI-ME310-hotel
A Stanford GEDI x NUS CDE4301 project exploring how design and technology can redefine luxury hospitality through a seamless, human-centered, and fully automated hotel check-in experience.

---

## 📝 How to Update the Interim Report (if you want to try it out)

This guide will help you edit `docs/interim-report.md` using Git and Markdown, even if you're new to these tools!

### Prerequisites
1. Install Git: [Download Git](https://git-scm.com/downloads)
2. Install a code editor: [VS Code](https://code.visualstudio.com/) or [Cursor](https://cursor.sh/) (recommended)
3. Clone this repository to your computer

### Getting Started with Git

#### 1. Clone the Repository (First Time Only)
```bash
git clone https://github.com/YOUR-USERNAME/GEDI-ME310-hotel.git
cd GEDI-ME310-hotel
```

#### 2. Before Making Changes (Always Do This First!)
```bash
# Make sure you have the latest version
git pull origin main
```

#### 3. Make Your Changes
Open `docs/interim-report.md` in your code editor and make your edits using Markdown syntax (see below).

#### 4. Save and Push Your Changes
```bash
# Check what files you changed
git status

# Add your changes
git add docs/interim-report.md

# Commit with a descriptive message
git commit -m "Updated [section name] in interim report"

# Push to GitHub
git push origin main
```

### Markdown Basics

Markdown is a simple way to format text. Here are the most common things you'll need:

#### Headings
```markdown
# Heading 1
## Heading 2
### Heading 3
```

#### Text Formatting
```markdown
**bold text**
*italic text*
`inline code or technical term`
```

#### Lists
```markdown
- Bullet point 1
- Bullet point 2
  - Sub-bullet (indent with 2 spaces)

1. Numbered item 1
2. Numbered item 2
```

#### Links
```markdown
[Link text](https://example.com)
```

#### Images
```markdown
![Alt text](../assets/images/your-image.png)
```

#### Videos
```markdown
[![Video Title](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://youtu.be/VIDEO_ID)
```

#### Quotes/Callouts
```markdown
> This is a quote or callout box
```

### Common Tasks

#### Adding a New Section
1. Use `###` for main sections
2. Leave blank lines before and after headings
3. Keep consistent formatting with existing sections

#### Adding Images
1. Place image files in `assets/images/`
2. Reference them using: `![Description](../assets/images/filename.png)`

#### Adding Videos
1. Upload video to YouTube (easier for embedding)
2. Use the YouTube embed format (see Markdown Basics above)
3. Or place video in `assets/videos/` and reference it

### Troubleshooting

**"I have merge conflicts!"**
- This happens when someone else edited the same lines
- Ask for help or use: `git pull --rebase origin main`

**"I made a mistake in my commit!"**
- You can undo your last commit: `git reset --soft HEAD~1`
- Then make your corrections and commit again

**"How do I preview my Markdown?"**
- VS Code: Press `Cmd+Shift+V` (Mac) or `Ctrl+Shift+V` (Windows)
- Or use an online preview: [StackEdit](https://stackedit.io/)

### Need Help?
- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [Git Tutorial](https://www.atlassian.com/git/tutorials)
- Ask the team on Slack/WhatsApp!
