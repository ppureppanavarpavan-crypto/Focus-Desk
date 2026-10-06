# Focus Desk

A calm, single-file Pomodoro timer and to-do list for making progress one focused session at a time. Focus Desk has no dependencies or build step and works on desktop and mobile.

## Features

- 25-minute focus, 5-minute short break, and 15-minute long break timers
- Start, pause, reset, and timer progress indicator
- Add, complete, and remove tasks; clear completed tasks in one click
- Daily completed focus-session count
- Tasks, session count, and timer state saved in your browser with `localStorage`

Your data stays in the browser on the device where you use the app. It is not synced between devices. The daily session count rolls over based on your local date; tasks remain until you remove them.

## Run locally

Open `index.html` in a modern browser. No installation or server is required.

## Publish with GitHub Pages

1. Create a GitHub repository named `focus-desk`.
2. Add `index.html` and this `README.md` to the repository's `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. After GitHub Pages finishes deploying, use the URL shown in the Pages settings.

## Add a screenshot

Capture the app in a browser at desktop or mobile width and save the image in the repository (for example, `screenshot.png`). Then add this to the README, replacing the example filename if needed:

```markdown
![Focus Desk timer and task list](screenshot.png)
```

The app does not bundle a screenshot generator; capture one with your browser or operating system.
