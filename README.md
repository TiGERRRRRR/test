# Pocket Arcade: Snake & Stackfall

A small offline game app with two games:

- **Snake**: the classic phone game. Eat food to grow longer and don't hit the walls or your own tail. The snake speeds up every 5 bites, and every 5th bite a bonus bug appears that you have to catch before it disappears.
- **Stackfall**: a falling-blocks puzzle game. Fill a row to clear it. Clearing rows on back-to-back pieces earns combo points. From level 3 on, five-cell pieces also start to fall.

High scores are saved on your device. It's all in plain HTML, CSS and JavaScript, with nothing to build and no libraries.

## Play

**Quick:** open `index.html` in any browser.

**As an installed app (phone or desktop, works offline):** the files must be hosted over HTTPS. The easiest way is GitHub Pages:
1. On GitHub, go to the repo's **Settings → Pages**.
2. Under "Build and deployment", pick **Deploy from a branch**, then choose this branch and the `/ (root)` folder, and save.
3. Open the link GitHub shows you, then:
   - **Android / Chrome / Edge:** tap **⬇ Install app** in the menu, or use the browser's menu → *Install app*.
   - **iPhone / iPad (Safari):** tap **Share → Add to Home Screen**.

After that it gets its own icon and opens full-screen like any other app, even offline.

To test locally: `python3 -m http.server`, then open http://localhost:8000.

## Controls

| | Snake | Stackfall |
|---|---|---|
| Keyboard | Arrows / WASD | ← → move, ↑ or X rotate, ↓ soft drop, Space hard drop |
| Touch | Swipe on the board or use the on-screen D-pad | Buttons, or tap = rotate, swipe ←/→ = move, swipe ↓ = drop |
| Pause | P / Esc / ❚❚ | P / Esc / ❚❚ |

The game pauses automatically when you switch away from it.
