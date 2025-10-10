# GitHub Pages Troubleshooting Guide

## Files Added to Fix Update Issues

I've created the following files to ensure your GitHub Pages updates properly:

1. **`_config.yml`** - Jekyll configuration file
2. **`.github/workflows/deploy-pages.yml`** - GitHub Actions workflow for automatic deployment
3. **`.gitignore`** - Prevents build artifacts from being tracked

## Steps to Enable Auto-Updates

### 1. Configure GitHub Pages Settings

Go to your GitHub repository:

1. Navigate to **Settings** → **Pages**
2. Under "Build and deployment":
   - **Source**: Select "GitHub Actions" (NOT "Deploy from a branch")
3. Save the changes

### 2. Push These New Files

```bash
git add _config.yml .github/ .gitignore
git commit -m "Add GitHub Pages configuration and workflow"
git push origin main
```

### 3. Verify Workflow is Running

1. Go to your repository on GitHub
2. Click on the **Actions** tab
3. You should see a workflow running called "Deploy Jekyll site to Pages"
4. Wait for it to complete (usually takes 1-2 minutes)

## Common Issues & Solutions

### Issue 1: Changes Not Appearing

**Cause:** Browser caching

**Solutions:**

- Hard refresh: `Ctrl + F5` (Windows) or `Cmd + Shift + R` (Mac)
- Clear browser cache
- Try opening in incognito/private mode
- Try a different browser

### Issue 2: Workflow Not Running

**Cause:** GitHub Actions not enabled or wrong source selected

**Solution:**

1. Go to **Settings** → **Pages**
2. Ensure **Source** is set to "GitHub Actions" (not "Deploy from a branch")
3. Go to **Settings** → **Actions** → **General**
4. Ensure "Allow all actions and reusable workflows" is selected

### Issue 3: Build Failing

**Cause:** Invalid markdown or Jekyll configuration

**Solution:**

1. Check the **Actions** tab for error details
2. Look at the build logs
3. Fix any markdown syntax errors
4. Ensure all internal links are valid

### Issue 4: 404 Errors for Pages

**Cause:** File naming or path issues

**Solution:**

- Ensure all `.md` files are lowercase
- Use relative links: `[text](folder/file.md)`
- Don't use absolute URLs for internal links

### Issue 5: Slow Updates (5-10 minutes)

**Cause:** GitHub's CDN caching

**Solution:**

- This is normal - wait up to 10 minutes
- Check workflow completion in Actions tab first
- Then hard refresh your browser

## How to Update Your Site Going Forward

### For Each Update:

```bash
# 1. Make your changes to markdown files
# 2. Add and commit changes
git add .
git commit -m "Update documentation"

# 3. Push to GitHub
git push origin main

# 4. Wait 1-2 minutes for GitHub Actions to build
# 5. Hard refresh your browser (Ctrl + F5)
```

### Monitoring Updates:

1. **Check Actions Tab**: See if workflow completed successfully
2. **Check Workflow Time**: Look at the timestamp of last successful deployment
3. **Hard Refresh Browser**: Always do this after deployment completes

## Forcing a Rebuild

If changes still aren't appearing, trigger a manual rebuild:

### Method 1: Via GitHub Website

1. Go to **Actions** tab
2. Click "Deploy Jekyll site to Pages" workflow
3. Click "Run workflow" button
4. Select branch and click "Run workflow"

### Method 2: Empty Commit

```bash
git commit --allow-empty -m "Trigger rebuild"
git push origin main
```

## Testing Locally (Optional)

To preview changes before pushing:

```bash
# Install Jekyll (one-time)
gem install jekyll bundler

# Serve site locally
jekyll serve

# Open http://localhost:4000 in browser
```

## Quick Checklist After Pushing

- [ ] Changes pushed to `main` branch
- [ ] Go to Actions tab - workflow is running/completed
- [ ] Wait for green checkmark (✓)
- [ ] Hard refresh browser (`Ctrl + F5`)
- [ ] Check timestamp on page matches your commit

## Need More Help?

If issues persist:

1. Check GitHub Status: https://www.githubstatus.com/
2. Review build logs in Actions tab
3. Ensure you're viewing the correct branch
4. Check if custom domain is configured correctly

---

**Last Updated:** October 10, 2025
