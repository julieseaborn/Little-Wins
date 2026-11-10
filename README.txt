LITTLE WINS — iPhone Home Screen web app

WHAT'S INCLUDED
- Daily household and personal tasks
- XP and levels
- Reward milestones
- Local saved progress (stored in this browser on this device)
- Home Screen / offline PWA support

IMPORTANT
To install as a true iPhone Home Screen web app, these files must be hosted on an HTTPS website.
The app currently saves progress in Safari's local storage. It does not sync between devices or provide cloud backup.
Do not clear Safari website data if you want to preserve local progress.

EASIEST HOSTING ROUTE (GitHub Pages — free)
1. On your iPhone or a computer, create/sign in to a GitHub account at https://github.com
2. Create a new PUBLIC repository named little-wins (or another name).
3. Upload all five files from this folder: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for GitHub Pages to publish. The site address will look like:
   https://YOUR-USERNAME.github.io/little-wins/
8. Open that address in Safari on your iPhone.
9. Tap the Share icon (square with arrow) > Add to Home Screen.
10. Keep "Open as Web App" enabled if shown, then tap Add.
11. Open Little Wins from the new Home Screen icon.

You can also host the files on another HTTPS static hosting service. The exact menus may vary.

HOW TO USE
- The current day's tasks are shown automatically based on your iPhone's date.
- Check tasks to earn XP.
- XP and checkmarks are saved locally on that device/browser.
- Use the week row to preview other days.
- Reset today clears today's checkmarks and reverses their XP.

CUSTOMIZATION
The task schedule, point values, colours and rewards are in index.html. This is a first working version; the weekly tasks and rewards can be adjusted.
