### 🌸 **YūreiTube - Ghostly Fast YouTube Downloader** 🌸  

---

## 🚀 **YūreiTube: Your Ultimate YouTube Video Downloader** 🎥  

**YūreiTube** (幽霊チューブ) is a **lightning-fast, parallelized YouTube downloader** built with **Node.js & TypeScript**, leveraging **child processes** to handle multiple downloads simultaneously without blocking the main thread. Inspired by the mysterious speed of **yūrei (ghosts)** in Japanese folklore, this tool works like a **phantom**, quickly fetching your favorite videos in the background with minimal resource usage.  

---

## 🌟 **Features**
✅ **Parallelized Downloads** – Download multiple videos simultaneously using **child processes**.  
✅ **CLI Interface** – Simple and intuitive command-line controls for a seamless experience.  
✅ **High-Speed Performance** – Uses `youtube-dl-exec` for efficient downloading.  
✅ **Customizable Output** – Saves videos in an organized folder with proper naming.  
✅ **Automatic Process Handling** – Each download runs independently, preventing lag or crashes.  
✅ **Cross-Platform Support** – Works on **Windows, macOS, and Linux**.  

---

## 🎮 **How It Works**
1️⃣ **Enter the YouTube URL** – Paste the link in the CLI.  
2️⃣ **Start Downloading** – YūreiTube spawns a **child process** that fetches your video.  
3️⃣ **Monitor Progress** – The main process receives **real-time updates** from workers.  
4️⃣ **Enjoy Your Video!** – Your downloaded video is saved in the `downloads/` folder.  

---

## 🔥 **Why YūreiTube?**
Unlike traditional YouTube downloaders that **block the main thread** during downloads, **YūreiTube utilizes child processes**, ensuring that **each download runs independently**. This means **faster, smoother performance** without lag! 🏎️💨  

---

## 📦 **Installation**
Clone the repository and install dependencies:  
```sh
git clone https://github.com/yureitube.git
cd yureitube
npm install
```
Compile TypeScript:  
```sh
npx tsc
```
Run YūreiTube:  
```sh
node dist/main.js
```

---

## 🎯 **Commands**
| Command | Description |
|---------|------------|
| `1` | Start a new YouTube video download |
| `2` | View active downloads |
| `3` | Exit the application |

---

## 🏆 **Upcoming Features**
✨ **Download audio-only mode** 🎵  
✨ **Progress bar for live tracking** 📊  
✨ **Web UI for managing downloads** 🌐  
✨ **Auto-conversion to MP4/MP3** 🔄  

---

### 🌊 **Embrace the Phantom Speed of YūreiTube!** 👻  
Faster than the wind, quieter than a shadow—let **YūreiTube** handle your YouTube downloads like a true digital specter! 🚀🎬  

---
