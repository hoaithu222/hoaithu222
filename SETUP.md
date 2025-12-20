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

### 4. Generate Snake Animation (First Time)
After pushing the code:
1. Go to **Actions** tab in your repository
2. Select **"Generate Snake Animation"** workflow
3. Click **"Run workflow"** → **"Run workflow"** button
4. Wait for the workflow to complete (usually 1-2 minutes)
5. The snake animation will appear in your README automatically

**Note:** The animation updates daily automatically, but you need to run it manually the first time.

### 5. Customize Colors & Theme
The current theme uses:
- Primary color: `A970FF` (Purple)
- Theme: `tokyonight`
- Background: `0D1117` (Dark)

To change colors, search and replace `A970FF` with your preferred hex color in `README.md`.

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

- **Typing SVG**: Uses `readme-typing-svg.vercel.app` - should work immediately
- **Snake Animation**: Requires first manual workflow run, then updates daily
- **GitHub Stats**: Update in real-time automatically
- **All badges and stats**: Automatically generated
- **Repository**: Must be **public** for stats to work properly
- **Workflow Permissions**: Make sure Actions have write permissions

## 🎯 Next Steps

1. Commit and push all files to your `hoaithu222` repository
2. Update social media links
3. Wait for GitHub Actions to run (or trigger manually)
4. Visit `https://github.com/hoaithu222` to see your profile!

---

**Need help?** Check out [GitHub Profile README Generator](https://github.com/rahuldkjain/github-profile-readme-generator) for more ideas!

