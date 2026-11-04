# LiteClip

A tiny Windows app that clips your gameplay. It keeps the last 30 seconds of your screen and sound in memory,
and saves a clip when you press a key.

**[Download LiteClip.exe](https://github.com/LabelTranslator/LiteClip/releases/latest/download/LiteClip.exe)**,
run it, click **Install**. That's it: no account, no admin rights.

- **F8** saves a 720p clip, **Shift+F8** saves 1080p (change the keys in Settings)
- Click the tray icon to open your clips: watch, trim on the timeline, pick game/mic audio, rename, star, sort, delete
- **Copy for Discord** puts a small copy on your clipboard: paste it in Discord with Ctrl+V
- **Get link** uploads a clip to a free file host and copies the link
- **Import from Medal** brings over your Medal clips (titles, games, favorites). Clips you named stay in full quality; the rest can be compressed to save space
- Add your own videos by dragging them into the window
- Uses your graphics card's video encoder (NVIDIA, AMD or Intel), so games keep their FPS
- Updates itself when it starts

## First start

Windows may show **"Windows protected your PC"** because LiteClip isn't code-signed.
Click **More info** → **Run anyway**.

The first start downloads LiteClip's video engine (FFmpeg, about 85 MB) once.

## Privacy

Everything runs on your PC. Nothing is uploaded unless you click **Get link**; then that one clip is uploaded to a
free public file host (qu.ax, pomf.lain.la or x0.at; litterbox.catbox.moe for 1-3 day links), and anyone with the link can watch it.

## Uninstall

Windows Settings → Apps → LiteClip → Uninstall. Your clips stay in `Videos\LiteClip`.

---

LiteClip uses [FFmpeg](https://ffmpeg.org) (GPL v3; see the notes in the "Video engine" release) and Microsoft Edge WebView2.
