# Fantasy Football Stats Dashboard - Vercel Deployment

## 🚀 How to Deploy to Vercel

### Option 1: Drag & Drop (EASIEST - 2 minutes!)

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub, GitLab, or Email (it's free!)
3. Click "Add New" → "Project"
4. Drag and drop the `vercel-deploy` folder into the browser
5. Click "Deploy"
6. Wait 30 seconds
7. Copy your link and share with your league!

### Option 2: Vercel CLI

```bash
npm i -g vercel
cd vercel-deploy
vercel
```

## 📁 Files to Upload

Upload these files to Vercel:
- `index.html` (the main dashboard file)
- `vercel.json` (configuration)

That's it! Just these 2 files.

## 🔄 Updating Your Dashboard

To update with new stats:

**Option A: Users upload JSON each time (current setup)**
- Users visit your Vercel link
- They upload their JSON file
- Dashboard loads with their data

**Option B: Auto-load JSON (requires one extra step)**
- Add your JSON file to the deployment
- Edit index.html to auto-load it
- Redeploy to Vercel
- Users see stats automatically without uploading

## 📝 Your Vercel Link

After deployment, you'll get a link like:
```
https://your-fantasy-stats.vercel.app
```

Share this with your league!

## 🔧 Troubleshooting

**Problem:** Dashboard doesn't load
**Solution:** Make sure both index.html and vercel.json are uploaded

**Problem:** Can't upload JSON file
**Solution:** The file must be named with .json extension

## 💡 Pro Tips

1. **Custom Domain:** Vercel lets you add a custom domain for free
2. **Auto-Deploy:** Connect to GitHub to auto-deploy on updates  
3. **Multiple Seasons:** Keep different Vercel projects for each season

## Need Help?

The dashboard is self-contained in index.html. No build process needed!
