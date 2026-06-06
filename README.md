# 🏃‍♂️ Subway Surfers Clone
## Author: Vikram Singh
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/bubbls/subwaysurfersmerge/img/FirstAvatar.png" alt="Subway Surfers Banner" width="1200" max-width="100%">
  
  <h3>Developed & Customized by **Vikram Singh**</h3>

  <p align="center">
    A lightweight, fully functional browser-based remake of the classic endless runner game, compressed into an easy-to-deploy architecture.
  </p>

  <p align="center">
    <a href="#-quick-start">🚀 Quick Start</a> •
    <a href="#-interactive-controls-simulator">🕹️ Controls Simulator</a> •
    <a href="#-features">🌟 Features</a> •
    <a href="#-how-to-deploy">🌐 Deployment</a>
  </p>
</div>

---

## 🚀 Quick Start

Because this project uses a unified `<base>` URL architecture, you can run the entire game using just **one single HTML file**. 

1. Copy your `index.html` file containing your `<head>` setup.
2. Double-click it to open it directly in any modern browser—no heavy web servers required!

---

## 🕹️ Interactive Controls Simulator

*Click the interactive buttons below to preview how to play the game on your keyboard:*

<table>
  <tr>
    <td align="center"><strong>Action</strong></td>
    <td align="center"><strong>Keyboard Key</strong></td>
    <td align="center"><strong>Interactive Trigger</strong></td>
  </tr>
  <tr>
    <td>Jump / Leap Over Trains</td>
    <td align="center"><code>▲ Arrow Up</code> / <code>W</code></td>
    <td><button onclick="alert('⚡ JUMP! Vikram dodges the guard obstacle!')">模拟 Jump</button></td>
  </tr>
  <tr>
    <td>Roll / Duck Under Barriers</td>
    <td align="center"><code>▼ Arrow Down</code> / <code>S</code></td>
    <td><button onclick="alert('🛹 ROLL! Sliding clean under the signal pole.')">模拟 Roll</button></td>
  </tr>
  <tr>
    <td>Move Left</td>
    <td align="center"><code>◀ Arrow Left</code> / <code>A</code></td>
    <td><button onclick="alert('🏃‍♂️ LEFT LANE! Snagged 3 gold coins.')">模拟 Left</button></td>
  </tr>
  <tr>
    <td>Move Right</td>
    <td align="center"><code>▶ Arrow Right</code> / <code>D</code></td>
    <td><button onclick="alert('🏃‍♂️ RIGHT LANE! Safely avoided the oncoming train.')">模拟 Right</button></td>
  </tr>
  <tr>
    <td>Activate Hoverboard</td>
    <td align="center"><code>Spacebar</code></td>
    <td><button onclick="alert('🏄‍♂️ HOVERBOARD ACTIVATED! Double-tap protection active.')">模拟 Hoverboard</button></td>
  </tr>
</table>

---

## 🌟 Features

*   **Ultra-Lightweight Architecture:** Runs entirely through an optimized single-file layout fetching cloud-based assets.
*   **Open Graph Optimized:** Built-in `<meta>` data ensures rich preview cards when sharing your game link on Discord, Twitter, or WhatsApp, keeping your name credited.
*   **Embedded Dependencies:** Securely hooks into external core engines (`4399.z.js`) via the `cdn.jsdelivr.net` network for consistent uptime.

---

## 🛠️ Deep Dive: The Code Architecture

Your HTML structure utilizes advanced `<base>` target rendering to make asset paths incredibly clean:

```html
<!-- The framework core that powers this project -->
<base href="[https://cdn.jsdelivr.net/gh/bubbls/subwaysurfersmerge/](https://cdn.jsdelivr.net/gh/bubbls/subwaysurfersmerge/)">
<script src="4399.z.js"></script>