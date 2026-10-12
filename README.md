# BEU Study Hub

A free study app for BEU students: pick branch and semester, open a topic, watch its YouTube video, tick it done. Progress is saved in the browser.

## Add content
Edit `data.js`. For each topic put the YouTube video ID (from `youtube.com/watch?v=VIDEO_ID`) in `video`. Add a notes link in `notes` if you have one.

## 1. Create the GitHub repository
1. Go to https://github.com/new, name it `beu-study-hub`, keep it Public, click **Create repository**.
2. Unzip this project, open a terminal inside the folder, then run:

```bash
git init
git add .
git commit -m "First version"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/beu-study-hub.git
git push -u origin main
```
(No terminal? On the new repo page click **uploading an existing file** and drag in all files.)

## 2. Deploy on Vercel
1. Sign in at https://vercel.com with your GitHub account.
2. Click **Add New > Project**, pick `beu-study-hub`, click **Import**.
3. Leave Framework as **Other**, leave build settings empty, click **Deploy**.
4. You get a live link like `beu-study-hub.vercel.app`. Every `git push` redeploys automatically.

## Ideas to grow it
Previous year questions per subject, a syllabus tab, user login with Supabase to save progress across devices, and an admin page to add videos without editing code.
