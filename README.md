# TwyMini Desktop

<p align="center">
  <img src="https://twymini.netlify.app/icon.png" alt="TwyMini Logo" width="96">
</p>

<h1 align="center">TwyMini Desktop</h1>

<p align="center">
  <strong>Your intelligent AI assistant, available directly from your desktop.</strong>
</p>

<p align="center">
  <a href="https://twyminidesk.web.app">Download Desktop</a> •
  <a href="https://twymini.netlify.app">Web App</a> •
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#development">Development</a> •
  <a href="#building">Building</a>
</p>

<p align="center">
  <a href="https://twyminidesk.web.app">
    <strong>⬇️ Download TwyMini Desktop</strong>
  </a>
</p>

---

## ✨ About

**TwyMini Desktop** is the desktop edition of **TwyMini AI**, an intelligent multi-device AI assistant developed by **TwyNexa Labs**.

TwyMini brings AI tools into a dedicated desktop application instead of requiring you to keep a browser tab open.

The TwyMini platform includes features such as **Google Sign-In, Deep Search, AI Image Generation, Multi-Model Reasoning, and a Live Canvas Workspace**.

🌐 **Web version:** https://twymini.netlify.app

🖥️ **Official Desktop Download:** https://twyminidesk.web.app

---

## 📥 Download

### Official TwyMini Desktop Download

Get the latest desktop version from the official TwyMini Desktop website:

**👉 https://twyminidesk.web.app**

The official download page provides the available desktop builds for supported operating systems.

<p align="center">
  <a href="https://twyminidesk.web.app">
    <strong>🚀 Download TwyMini Desktop</strong>
  </a>
</p>

> **Tip:** For the safest installation, always download TwyMini Desktop from the official download page or the project's official GitHub Releases.

---

## 🚀 Features

### 🤖 AI Assistant

Interact with TwyMini through a modern AI chat interface designed for everyday productivity, research, coding, and creative work.

### 🔎 Deep Search

Research topics using TwyMini's search capabilities and get more comprehensive answers.

### 🧠 Multi-Model Reasoning

TwyMini is designed to work with multiple AI models and reasoning capabilities to provide flexible responses for different tasks.

### 🎨 AI Image Generation

Generate images using TwyMini's integrated AI image-generation capabilities.

### 🖼️ Live Canvas Workspace

Use the Live Canvas Workspace for visual and interactive AI-assisted work.

### 🔐 Google Sign-In

Sign in using your Google account and keep your TwyMini experience connected across supported devices.

### 🖥️ Desktop Application

TwyMini Desktop provides a dedicated desktop experience without requiring the web application to remain open in a browser.

### 🔔 Desktop Notifications

Receive supported TwyMini notifications directly through your operating system.

### ⚡ Fast & Lightweight

Built with a modern desktop architecture to provide a responsive experience while keeping the application lightweight.

---

## 🖥️ Supported Platforms

| Platform | Status      |
| -------- | ----------- |
| Windows  | ✅ Supported |
| macOS    | ✅ Supported |
| Linux    | ✅ Supported |

> Platform availability depends on the corresponding release build.

---

## 📦 Installation

### Windows

1. Visit the **[official TwyMini Desktop download page](https://twyminidesk.web.app)**.
2. Download the latest Windows installer.
3. Run the installer.
4. Follow the setup wizard.
5. Launch **TwyMini Desktop** from the Start Menu or desktop shortcut.

### macOS

1. Visit the official download page.
2. Download the latest macOS build.
3. Open the application.
4. If macOS displays a security warning, approve the application through **System Settings → Privacy & Security** when appropriate.

### Linux

Download the appropriate Linux package from the official download page.

For an AppImage:

```bash
chmod +x TwyMini*.AppImage
./TwyMini*.AppImage
```

---

## 🛠️ Development

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* Rust
* Cargo
* Tauri CLI
* Git

Clone the repository:

```bash
git clone https://github.com/Suvasoura/TwyMiniDesktop.git
cd TwyMiniDesktop
```

Install dependencies:

```bash
npm install
```

Start the development application:

```bash
npm run tauri dev
```

---

## 🏗️ Building

Build the production application with:

```bash
npm run tauri build
```

Tauri will generate the platform-specific release bundles.

### Windows

```bash
npm run tauri build
```

The generated Windows installers can be found inside:

```text
src-tauri/target/release/bundle/
```

### macOS

For a universal macOS build:

```bash
npm run tauri build -- --target universal-apple-darwin
```

### Linux

```bash
npm run tauri build
```

Generated Linux packages can be found under:

```text
src-tauri/target/release/bundle/
```

---

## 📁 Project Structure

```text
TwyMiniDesktop/
│
├── src/
│   ├── ...
│   └──
│
├── src-tauri/
│   ├── src/
│   ├── icons/
│   ├── Cargo.toml
│   ├── Cargo.lock
│   └── tauri.conf.json
│
├── public/
│   └── ...
│
├── package.json
├── package-lock.json
├── vite.config.*
└── README.md
```

---

## 🔐 Security

Never commit API keys, private credentials, OAuth secrets, or other sensitive configuration to GitHub.

Use environment variables or a secure backend for private credentials.

Example:

```env
API_KEY=your_key_here
```

Add sensitive files to `.gitignore`:

```gitignore
.env
.env.*
!.env.example
```

---

## 🌐 TwyMini Web

You can also use TwyMini directly from your browser:

**https://twymini.netlify.app**

The web application provides the core TwyMini AI experience without requiring the desktop application.

---

## 🧩 Technology

TwyMini Desktop is built around modern web and native technologies, including:

* **Tauri** — lightweight cross-platform desktop framework
* **Rust** — native desktop backend
* **JavaScript / TypeScript** — application logic
* **HTML / CSS** — user interface
* **Node.js / npm** — development tooling

---

## 🗺️ Roadmap

* [ ] Improved desktop notifications
* [ ] More native desktop integrations
* [ ] Enhanced AI workspace
* [ ] Improved multi-device synchronization
* [ ] Additional AI models
* [ ] More customization options
* [ ] Performance improvements
* [ ] Automatic application updates
* [ ] Additional platform-specific features

---

## 🤝 Contributing

Contributions, ideas, bug reports, and feature requests are welcome.

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature/my-feature
```

3. Make your changes.
4. Test the application.
5. Commit your changes:

```bash
git commit -m "Add my feature"
```

6. Push your branch:

```bash
git push origin feature/my-feature
```

7. Open a Pull Request.

---

## 🐛 Bug Reports

If you encounter a problem with TwyMini Desktop, please open a GitHub Issue and include:

* Operating system
* TwyMini Desktop version
* Steps to reproduce the problem
* Expected behavior
* Actual behavior
* Relevant error messages or logs

**Never include API keys, passwords, OAuth secrets, or other private credentials in an issue.**

---

## 📄 License

See the repository's license file for the terms applicable to this project.

---

## 🏢 TwyNexa Labs

**TwyMini Desktop** is part of the TwyNexa Labs ecosystem.

Built with ❤️ by **TwyNexa Labs**.

### Official Links

* 🖥️ **Desktop Download:** https://twyminidesk.web.app
* 🌐 **TwyMini Web:** https://twymini.netlify.app
* 💻 **GitHub:** https://github.com/Suvasoura/TwyMiniDesktop

---

<p align="center">
  <strong>TwyMini — Intelligent AI, wherever you work.</strong>
</p>

<p align="center">
  Made with ❤️ by TwyNexa Labs
</p>
