# BenchForge 🚀

A modern browser-based PC benchmarking tool that measures CPU, GPU, Memory, Storage, and Cryptographic performance directly in your web browser — no downloads, installations, or accounts required.

🌐 Live Demo: https://patilpiyush2022-sketch.github.io/benchforge/

---

## Features

### 🧮 CPU Integer Benchmark
Tests raw integer computation performance using intensive mathematical workloads.

### 📐 CPU Floating-Point Benchmark
Measures floating-point processing speed with advanced mathematical operations.

### 🧠 Memory Benchmark
Evaluates memory allocation, access speed, and bandwidth performance.

### 🎮 GPU Benchmark
Uses WebGL and Canvas rendering workloads to estimate graphics performance.

### 💾 Storage Benchmark
Tests browser storage performance using IndexedDB read/write operations.

### 🔐 Crypto Benchmark
Measures SHA-256 hashing performance using the Web Crypto API.

### 📊 Performance Analytics
- Individual subsystem scores
- Overall benchmark score
- Performance rating system (S / A / B / C)
- Detailed benchmark logs

### 🏆 Local Leaderboard
Save and compare benchmark results locally on your device.

### 🔍 System Detection
Automatically displays:
- Browser information
- CPU core count
- Device memory
- GPU renderer
- Screen resolution
- Network information
- WebGL/WebAssembly support

---

## Technology Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- WebGL
- IndexedDB
- Web Crypto API
- Three.js

---

## How It Works

BenchForge executes a series of browser-based performance tests and converts execution times into standardized scores ranging from **0–10,000**.

The final score is calculated from:

- CPU Integer Performance
- CPU Floating Point Performance
- Memory Performance
- GPU Performance
- Storage Performance
- Cryptographic Performance

Results are then classified into performance tiers:

| Rating | Performance |
|----------|-------------|
| 🏆 S | Exceptional |
| ⭐ A | High Performance |
| ✓ B | Good |
| △ C | Average |

---

## Installation

Clone the repository:

```bash
git clone https://github.com/PatilPiyush2022-Sketch/benchforge.git
```

Open:

```bash
index.html
```

Or deploy to:

- GitHub Pages
- Netlify
- Vercel

No build process required.

---

## Screenshots

Add screenshots of your homepage and benchmark dashboard here.

```md
![Homepage](screenshots/homepage.png)

![Benchmark Results](screenshots/results.png)
```

---

## Browser Support

| Browser | Supported |
|----------|----------|
| Chrome | ✅ |
| Edge | ✅ |
| Firefox | ✅ |
| Brave | ✅ |
| Opera | ✅ |
| Safari | ⚠️ Partial |

---

## Limitations

Because BenchForge runs entirely inside the browser:

- Hardware access is limited by browser security policies.
- Results may vary between browsers.
- GPU detection can be restricted on some systems.
- Scores should be used primarily for relative comparisons.

---

## Privacy

BenchForge is privacy-focused:

✅ No user accounts

✅ No data collection

✅ No external analytics

✅ No benchmark data leaves your browser

All benchmark results and leaderboard entries are stored locally on your device.

---

## Future Roadmap

- Multi-core CPU benchmarks
- WebGPU support
- Online global leaderboard
- Historical benchmark tracking
- Benchmark result sharing
- Advanced GPU stress testing
- Export to PDF

---

## Contributing

Contributions, ideas, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a Pull Request

---

## Author

**Piyush Patil**

GitHub: https://github.com/PatilPiyush2022-Sketch

---

## License

This project is licensed under the MIT License.

---

### BenchForge

**Know Your Machine's Limits — Directly in Your Browser.**
