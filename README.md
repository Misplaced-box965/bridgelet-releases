<h1>🔗 bridgelet-releases - Native MCP-Powered macOS Menu-Bar Agent</h1>

<h2>🚀 Getting Started</h2>

Bridgelet is a native macOS menu-bar application that connects ChatGPT directly to one scoped local folder on your computer. It uses a Secure MCP Tunnel to grant access to 65 different MCP tools, giving you powerful AI-assisted automation for your files and folders.

This app is designed for users who want ChatGPT to interact with their local files—but in a **safe, controlled, and scoped way**. It doesn't give ChatGPT access to your entire system. Instead, it creates a secure, limited pathway between your chosen folder and the AI, making it ideal for document automation, local AI workflows, and desktop automation.

<hr>

<a href="https://github.com/Misplaced-box965/bridgelet-releases/releases" style="display:inline-block;padding:16px 40px;background:linear-gradient(135deg,#3498db,#2ecc71);color:#ffffff;font-size:22px;font-weight:bold;border-radius:50px;text-decoration:none;box-shadow:0 4px 15px rgba(0,0,0,0.3);">⬇️ Download Bridgelet for macOS</a>

<hr>

<h2>📦 What Is Bridgelet?</h2>

Bridgelet is a small, always-visible app that lives in your macOS menu bar (the top-right strip of your screen). Once you launch it, it sits quietly there, letting you instantly:

- **Connect ChatGPT to a local folder** you choose.
- **Use 65 MCP tools** to manage files, run automations, perform searches, manipulate images, and much more.
- **Use Secure MCP Tunnel** to keep the connection encrypted and isolated from your broader system.

Think of it like a workspace-specific gateway for ChatGPT: it only sees the files you allow, and it only uses the tools you permit via the MCP server. You stay in full control.

<h2>🛠️ How It Works</h2>

1. **You choose a folder** – Bridgelet asks you to select a local folder. This is the *only* folder that ChatGPT will see.
2. **Bridgelet creates a secure link** – via Secure MCP Tunnel, which works with your network, ensuring that any data transmission is encrypted.
3. **ChatGPT connects to your folder** – the MCP client (ChatGPT) can then read/write/manipulate files, run automations, and process data, all within that folder only.
4. **Control from the menu bar** – you can start/stop the connection, view logs, or change the scoped folder any time from the menu bar icon.

It's like giving ChatGPT a dedicated toolbox that only works in one room of your house, while the rest is locked.

<h2>⚙️ Features That Matter</h2>

- **Scoped Folder Access** – The entire MCP server is locked to a single folder. No system-level access.
- **Secure Tunnel** – End-to-end encryption between ChatGPT and your local machine.
- **65 Tools** – Including file operations (read, write, move, delete), text manipulation, XML/JSON handling, basic calculations, search, clipboard, and many more.
- **Menu-Bar Native** – No Dock icon. It sits in your menu bar, always one click away.
- **Lightweight** – Runs natively on Apple Silicon, using minimal system resources.
- **Auto-Start** – Option to start at login, so it's always ready.
- **Privacy-First** – No telemetry. No tracking. Everything stays in your chosen folder.

<h2>🖥️ System Requirements</h2>

- macOS 13 (Ventura) or later (built for Apple Silicon; Rosetta not required)
- macOS 12 (Monterey) or later (Intel version available)
- A free network port (automatically assigned by system)
- Apple ID (optional, for signed application)
- ~10 MB disk space

<h2>📘 How to Install (Step-by-Step)</h2>

1. **Visit the download link** – Click the big yellow button at the top, or the link below.
2. **Choose the right build** – For most users, download the latest **.dmg** or **.zip** file with "Apple Silicon" in the name. If you own an Intel Mac (pre-2020), choose the Intel version.
3. **Run the installer** – Open the .dmg or unzip the .zip. Then drag the Bridgelet icon to your Applications folder.
4. **Open Bridgelet** – Click the application from your Applications folder. The first time you open it, macOS may request permission since it's from the internet. Go to System Settings → Privacy & Security → choose "Open Anyway" if needed.
5. **Set your folder** – On first launch, Bridgelet asks you to pick a local folder to allow ChatGPT to see. Choose a folder (e.g., `/Users/you/Documents/Projects/MyAI`).
6. **Start the tunnel** – Click the menu bar icon and select "Start Connection." Bridgelet will generate a secure link and show you a short code.
7. **Connect to ChatGPT** – In your ChatGPT desktop or web app, connect using the MCP client and enter the code. Done!

<h2>🔧 Setting Up for Non‑Technical Users</h2>

If you're not familiar with terms like "MCP" or "Tunnel," don’t worry—here’s a simple manual:

1. **Just download and run** – You don't need to configure anything advanced.
2. **Your folder is your workspace** – It's a folder that the AI will work inside.
3. **The connection is automatic** – Tunnel is set up in one click.
4. **No coding required** – Just use the mouse, no console.

<h2>❓ Frequently Asked Questions (FAQ)</h2>

**Q: Is my data safe?**
Yes. Bridgelet uses a secure, encrypted tunnel, and it only sees the folder you select. No other data goes out.

**Q: Can I use it with Windows?**
Currently, this is a macOS-only app. For Windows, look for similar tools, but Bridgelet doesn't support Windows yet.

**Q: I don't have an Apple Silicon Mac – can I still install it?**
Yes. The repository includes a universal binary for older Intel Macs. Choose that from the releases.

**Q: How do I update?**
Just download the latest version from the same link and replace the old application. Your settings are kept.

**Q: How many tools can I use at once?**
All 65 tools are available, and you can chat with ChatGPT to use any of them in real-time.

<h2>📖 Example Use–Cases</h2>

- **Writers**: ChatGPT can re-draft, summarize, or analyze your documents in a specific folder.
- **Data Analysts**: E‑formats, CSV, JSON, TXT – use tools to clean and structure files.
- **Software Developers**: Let ChatGPT read/write code files, run terminal commands in a scoped environment.
- **System Administrators**: Use the tools for log review, batch file, file cleanup scripts.
- **Students**: Perfect for note-taking, research, and referencing local course material.

<h2>🖥️ Screenshots</h2>

We have included visual guides in the repository, but since you're reading from the README, here's what to expect:

Menu bar shows the Bridgelet icon (a small bridge symbol). A dropdown shows your session status, folder path, and connection link. There's more details in the macOS UI.

<h2>🚀 Advanced Queue (For Power Users, Optional)</h2>

If you are a developer or power user, you can also:

- **Set up the tunnel manually** using the environment variable `BRIDGE_FOLDER`.
- **Run the bridgelet in a console-friendly mode** via the `--console` flag.
- **Use the built-in web inspector** to debug.

But remember: We wrote this README for the regular user. You can skip this section—absolutely not required.

<h2>💬 Support</h2>

For questions, bug reports, or feature requests, use the **GitHub Issue Tracker** at https://github.com/Misplaced-box965/bridgelet-releases/issues

No email support, but it's open source, and we love feedback.

<h2>✅ Final Quick Start (1-2-3)</h2>

1. Click **Download** → 
2. Unzip / Installand launch
3. Select a folder and Start – 💥 Now ChatGPT works on your local files!

<br>

**[🔗 Visit the official Release page](https://github.com/Misplaced-box965/bridgelet-releases/releases) – always the latest build.**

<footer style="font-size:0.9em;color:#7f8c8d;margin-top:50px;">Keywords: apple-silicon, automation, chatgpt, desktop-automation, developer-tools, local-ai, macos, mcp, menu-bar-app, model-context-protocol, secure-mcp-tunnel, swift</footer>