# prj-frontend-node.zimin.dev

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 16 16%22><text y=%2214%22 font-size=%2216%22>👨‍💻</text></svg>">
<title>Node Infrastructure | Sasha Zimin</title>
<style>
  body {
    background: #0f0f1a;
    color: #e0e0e0;
    font-family: 'Courier New', Courier, monospace;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    gap: 2rem;
    padding: 2rem;
    position: relative;
    overflow: hidden;
  }

  #bg-video {
    position: fixed;
    top: 0; left: 0;
    width: 100vw;
    height: 100vh;
    object-fit: cover;
    z-index: 0;
    pointer-events: none;
    filter: brightness(0.3) contrast(1.2);
  }
.node {
    background: rgba(30,30,60,0.8);
    border: 4px solid;
    border-image: linear-gradient(45deg, #39ff14, #8e2de2) 1;
    border-radius: 1rem;
    padding: 1.5rem;
    width: 300px;
    box-shadow: 0 0 20px rgba(0,255,255,0.1);
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 2s forwards;
    position: relative;
    z-index: 1;
}

.node:nth-child(1) { animation-delay: 0.5s; }
.node:nth-child(2) { animation-delay: 1s; }
.node:nth-child(3) { animation-delay: 1.5s; }
.node:nth-child(4) { animation-delay: 2s; }
.node:nth-child(5) { animation-delay: 2.5s; }

  h2 {
    margin: 0 0 0.5rem;
  }
  .codename {
    font-weight: bold;
    color: #00ffff;
  }
  .CELESTIAL { color: #ff9900; }
  .PREDATOR { color: #ff33cc; }
  .VALOR { color: #33ccff; }
  .SENTINEL { color: #ffff66; }
  .VORTEX { color: #ff66ff; }

  @keyframes fadeInUp {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
</style>
</head>
<body>

  <video id="bg-video" autoplay muted loop playsinline>
    <source src="/video/video2.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <div class="node" id="node1">
    <h2>🚀 Nexus Node</h2>
    <p>Role: Sync all nodes, UPS protect, 24/7 uptime</p>
    <p>OS: Windows 11 Pro<br>CPU: i3 8core (3.6GHz)<br>GPU: Intel Alder Lake 3.6GB</p>
    <p>RAM: 8GB DDR4 (3200MHz)<br>Storage: NVMe 512GB</p>
    <p class="codename CELESTIAL">Code Name: CELESTIAL</p>
  </div>
  <div class="node" id="node2">
    <h2>💪 Titan Node</h2>
    <p>Role: Heavy workloads, Wake on LAN, cold backup</p>
    <p>OS: Windows 10 Pro<br>CPU: Ryzen 9 16(32)core (5GHz)<br>GPU: Nvidia GTX 1070 TI 8Gb</p>
    <p>RAM: 64GB DDR4 (3200MHz)<br>Storage: NVMe 512GB\3TB RAID-1</p>
    <p class="codename PREDATOR">Code Name: PREDATOR</p>
  </div>
  <div class="node" id="node3">
    <h2>📡 Pulse Node</h2>
    <p>Role: Mobile access, RDP, gaming</p>
    <p>OS: Android 14<br>CPU: Exynos + Snapdragon 3.4GHz<br>GPU: Mali-G710/Adreno VRAM 12GB</p>
    <p>RAM: 12GB LP-DDR5 (3200MHz)<br>Storage: UFS 256GB</p>
    <p class="codename VORTEX">Code Name: VORTEX</p>
  </div>
  <div class="node" id="node4">
    <h2>💻 Gold Node</h2>
    <p>Role: Web dev\design, portable use</p>
    <p>OS: Linux Dracula<br>CPU: Ryzen 5 6(12)core (4.6GHz)<br>GPU: Radeon Graphics  2Gb</p>
    <p>RAM: 16GB DDR4 (3200MHz)<br>Storage: NVMe 512GB</p>
    <p class="codename SENTINEL">Code Name: SENTINEL</p>
  </div>
  <div class="node" id="node5">
    <h2>⚓ Dock Node</h2>
    <p>Role: Web dev\design, portable workstation</p>
    <p>OS: Linux Dzen<br>CPU: Ryzen 5 6(12)core (4.6GHz)<br>GPU: Radeon Graphics 2Gb</p>
    <p>RAM: 16GB DDR4 (3200MHz)<br>Storage: NVMe 512GB</p>
    <p class="codename VALOR">Code Name: VALOR</p>
  </div>

</body>
</html>
```
