# 🚀 GitHub Profile Setup Guide

## 📋 Prerequisites

1. **Repository Setup**
   - Repository name must be exactly: `hoaithu222` (same as your GitHub username)
   - Repository must be **public**
   - Default branch should be `main` (or update workflow files if using `master`)

2. **Enable GitHub Actions**
   - Go to repository Settings → Actions → General
   - Enable "Workflow permissions" → Read and write permissions
   - Allow GitHub Actions to create and approve pull requests

## ⚙️ Configuration Steps

### 1. Update Social Links
Edit `README.md` and update the links in the "Let's Connect" section:
- Replace `https://your-portfolio-url.com` with your actual portfolio URL
- Replace `https://linkedin.com/in/yourprofile` with your LinkedIn profile
- Replace `mailto:your.email@example.com` with your email
- Replace `https://twitter.com/yourhandle` with your Twitter/X handle

### 2. Add Profile Image (Optional)
If you want to add your profile image:
- Upload `me.png` to the repository root
- Add this code at the top of README.md (after the typing animation):
  ```markdown
  <img src="me.png" alt="Profile" width="200" style="border-radius: 50%;"/>
  ```

### 3. Activate GitHub Actions
The workflows will automatically run:
- **Snake Animation**: Updates daily at midnight UTC
- **3D Contribution**: Updates daily at midnight UTC

You can also manually trigger them:
- Go to Actions tab → Select workflow → Run workflow

### 4. Customize Colors & Theme
The current theme uses:
- Primary color: `9D4EDD` (Purple)
- Theme: `tokyonight`
- Background: `0D1117` (Dark)

To change colors, search and replace `9D4EDD` with your preferred hex color in `README.md`.

## 🎨 Features Included

✅ Animated typing header  
✅ Profile views counter  
✅ GitHub stats (commits, contributions, etc.)  
✅ Top languages chart  
✅ Contribution streak  
✅ Activity graph  
✅ GitHub trophies  
✅ Snake animation (auto-updates)  
✅ 3D contribution graph (auto-updates)  
✅ Tech stack badges  
✅ Social media links  

## 📝 Notes

- The snake animation will appear after the first workflow run
- GitHub stats update in real-time
- All badges and stats are automatically generated
- Make sure your repository is public for stats to work properly

## 🎯 Next Steps

1. Commit and push all files to your `hoaithu222` repository
2. Update social media links
3. Wait for GitHub Actions to run (or trigger manually)
4. Visit `https://github.com/hoaithu222` to see your profile!

---

**Need help?** Check out [GitHub Profile README Generator](https://github.com/rahuldkjain/github-profile-readme-generator) for more ideas!

