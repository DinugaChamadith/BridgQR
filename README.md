<div align="center">

# 🔳 BridgQR

**Generate crisp, high-resolution QR codes at the speed of light — right in your browser.**

A production-ready, privacy-first QR code generator built with a futuristic UI, zero tracking, and no backend required.

[![MIT License](https://img.shields.io/badge/License-MIT-22d3ee.svg?style=flat-square)](LICENSE)
[![Made with HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-8b5cf6.svg?style=flat-square)](CONTRIBUTING.md)
[![No Tracking](https://img.shields.io/badge/Tracking-None-ec4899.svg?style=flat-square)](#-privacy)

[Live Demo](https://example.com) · [Report Bug](../../issues) · [Request Feature](../../issues)

</div>

---

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Customization](#-customization)
- [Project Structure](#-project-structure)
- [Privacy](#-privacy)
- [Browser Support](#-browser-support)
- [Deployment](#-deployment)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🌌 About the Project

**BridgQR** is a single-file, futuristic QR code generator that runs entirely client-side. It turns any URL into a crisp, high-resolution, fully customizable QR code — with real-time updates, instant PNG downloads, and copy-to-clipboard support.

Built with a strong focus on **privacy**, **performance**, and **design**, BridgQR requires no accounts, no sign-ups, no servers, and no tracking. Every QR code is generated locally in your browser.

> 💡 **Why BridgQR?** Most QR generators upload your links to a server, watermark the output, or limit your downloads. BridgQR does none of that.

---

## ✨ Features

### 🎨 Design & UX
- **Futuristic dark UI** with animated gradient orbs, aurora glow, and glassmorphism panels
- **Scroll-triggered reveal animations** powered by `IntersectionObserver`
- **Animated scanline overlay** across the QR preview
- **Sticky glass navbar** with a mobile hamburger menu
- **Toast notifications** for downloads, copies, and errors
- **Back-to-top button** and smooth scrolling
- **Full `prefers-reduced-motion` support** for accessibility

### ⚡ QR Generation
- **Real-time rendering** — the code updates as you type (debounced)
- **Adjustable resolution** — export from **256 px up to 1024 px**
- **Custom colors** — pick foreground and background with native color pickers
- **Error correction levels** — L / M / Q / H (highly resilient codes)
- **High-resolution PNG export** with smart, hostname-based filenames
- **Copy image to clipboard** via the modern `ClipboardItem` API
- **Live preview** with animated corner brackets

### 🔒 Privacy & Performance
- **100% client-side** — no backend, no API calls, no data leaves your device
- **No accounts, no cookies, no analytics**
- **Single HTML file** — deployable anywhere in seconds
- **Zero build step** — powered by Tailwind CDN and QRious
- **Fully responsive** — mobile-first layout from 320 px upward

---

## 🛠 Tech Stack

| Layer          | Technology                                                                 |
| -------------- | -------------------------------------------------------------------------- |
| **Markup**     | HTML5                                                                      |
| **Styling**    | [Tailwind CSS](https://tailwindcss.com/) (via CDN) + custom CSS            |
| **QR Engine**  | [QRious](https://github.com/neocotic/qrious) v4.0.2                        |
| **Fonts**      | [Inter](https://fonts.google.com/specimen/Inter) & [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) |
| **Animation**  | Native CSS + `IntersectionObserver`                                        |
| **Runtime**    | Vanilla JavaScript (ES6+)                                                  |

No frameworks. No bundlers. No dependencies to install.

---

## 🚀 Getting Started

### Prerequisites

You only need a **modern web browser**. That's it.

### Installation

**Option 1 — Clone the repository**

```bash
git clone https://github.com/your-username/bridgqr.git
cd bridgqr
