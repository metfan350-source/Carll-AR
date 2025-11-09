metfan350-source/carll-AR — iPhone-Ready Instructions
=====================================================

What you need in the repo (root):
- index.html  (this file)
- 1019_main_level.glb
- 1019_basement.glb
- 1019_main_level.usdz
- 1019_basement.usdz

How to make the USDZ files (Mac, using Apple's Reality Converter):
1) Open 1019_main_level.glb → File → Export → USDZ → name it EXACTLY: 1019_main_level.usdz
2) Open 1019_basement.glb → export as: 1019_basement.usdz
3) Upload both .usdz files along with index.html to your repo: https://github.com/metfan350-source/carll-AR

Turn on GitHub Pages:
- Repo → Settings → Pages → Source: Deploy from a branch
- Branch: main, Folder: / (root) → Save
- Your site: https://metfan350-source.github.io/carll-AR

Use it:
- Android: AR uses the .glb
- iPhone: AR uses the .usdz

If AR doesn't launch on iPhone:
- Make sure the filenames exactly match index.html
- Give Pages a minute to publish, then hard-refresh.
