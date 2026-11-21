# Awesome-Collaborative-Coding-Cloud-Ides

# Top Collaborative Coding & Cloud IDEs Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Browser-Based Cloud IDEs, Self-Hosted Remote Development Environments, Multiplayer Code Editors & WebContainer Workspaces*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Collaborative Coding & Cloud IDEs**. These tools provision, host, synchronize, and run full development environments, terminals, live app previews, and real-time multiplayer coding sessions directly in web browsers and remote containers across laptops, tablets, and cloud infrastructure.

**Examples** include Replit, GitHub Codespaces, Gitpod (Ona), StackBlitz, Codeanywhere, Glitch, CodeSandbox, AWS Cloud9, Eclipse Che, Coder, and pingdotgg/t3code (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted browser VS Code & cloud IDEs (`Code-Server`, `OpenVSCode Server`, `Eclipse Theia`, `Eclipse Che`), Cloud Development Environment (CDE) orchestrators (`Coder`, `Daytona`, `DevPod`), and modern collaborative/agentic coding interfaces (`pingdotgg/t3code`, `Zed`, `Judge0`) — ideal for remote engineering teams, educators, DevOps/platform engineers, and developers coding from any device.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[GitHub Codespaces](https://github.com)**  
  Cloud-hosted instant development environments integrated directly into GitHub repositories with Dev Containers, prebuilds, port forwarding, and browser/desktop VS Code support.

- **[Replit](https://replit.com)**  
  Collaborative browser-based IDE and cloud deployment platform featuring real-time multiplayer editing, built-in PostgreSQL/object storage, and autonomous Replit Agent scaffolding.

- **[Gitpod (Ona)](https://gitpod.io)**  
  Cloud Development Environment (CDE) platform automating ephemeral, reproducible workspaces for engineering teams and autonomous coding agents directly from Git branches.

- **[StackBlitz](https://stackblitz.com)**  
  Instant browser-native full-stack web IDE powered by WebContainers, running Node.js, Vite, Next.js, and npm directly inside the browser sandbox with zero server latency.

- **[CodeSandbox](https://codesandbox.io)**  
  Cloud development platform offering instant microVM sandboxes, live multiplayer collaboration, interactive PR previews, and shareable browser coding environments.

- **[Codeanywhere](https://codeanywhere.com)**  
  Cloud IDE and container workspace service providing browser-accessible VS Code/Theia editors, SSH/SFTP connections, and DevContainer provisioning.

- **[Glitch](https://glitch.com)**  
  Community-driven browser coding and instant web-app hosting platform featuring live collaborative editing, remixable projects, and zero-config Node.js/static previews.

- **[AWS Cloud9 (Legacy / AWS IDE Ecosystem)](https://amazon.com)**  
  Browser-based cloud IDE by Amazon Web Services offering pre-authenticated AWS CLI terminals, collaborative pair editing, and direct EC2/Lambda debugging.

- **[Firebase Studio (formerly Project IDX by Google)](https://google.com)**  
  Google's cloud-based agentic development workspace featuring Nix-configured environments, built-in Android/iOS/web emulators, and Gemini coding assistance.


## Open-Source GitHub Projects

- **[pingdotgg/t3code](https://github.com)**  
  Open-source collaborative and AI-native coding interface from Theo Browne (t3.gg) engineered for fast, streamlined developer workflows and modern code execution.

- **[Coder (`coder/coder`)](https://github.com)**  
  Flagship self-hosted open-source Cloud Development Environment (CDE) platform provisioning reproducible remote workspaces via Terraform across Docker, Kubernetes, AWS, GCP, and Azure.

- **[Code-Server (`coder/code-server`)](https://github.com)**  
  Popular open-source server allowing you to run VS Code on any remote Linux/macOS/Windows machine or VPS and access it securely through any web browser.

- **[OpenVSCode Server (`gitpod-io/openvscode-server`)](https://github.com)**  
  Upstream open-source server distribution maintained by Gitpod that runs the latest VS Code web client directly on remote machines with minimal patching.

- **[Eclipse Che (`eclipse-che/che`)](https://github.com)**  
  Kubernetes-native open-source developer workspace server and cloud IDE platform providing multi-user Devfile environments, browser editors, and enterprise SSO.

- **[Eclipse Theia (`eclipse-theia/theia`)](https://github.com)**  
  Extensible open-source cloud and desktop IDE framework built in TypeScript supporting VS Code extensions, custom branding, and browser-native architectures.

- **[Daytona (`daytonaio/daytona`)](https://github.com)**  
  Open-source Development Environment Manager and elastic sandbox runtime for spinning up standardized local, remote, or AI-agent coding workspaces with a single command.

- **[DevPod (`loft-sh/devpod`)](https://github.com)**  
  Client-only open-source tool ("Codespaces but open-source") that turns any `devcontainer.json` repository into a reproducible remote workspace over SSH, Docker, or Kubernetes without a central server.

- **[Zed (`zed-industries/zed`)](https://github.com)**  
  High-performance, GPU-accelerated open-source code editor in Rust featuring native real-time multi-buffer collaboration, voice chat, and remote SSH development.

- **[Judge0 (`judge0/judge0`)](https://github.com)**  
  Robust, scalable open-source online code execution system supporting 60+ programming languages inside isolated sandboxes—powering collaborative coding platforms and technical interviews.

- **[Piston (`engineer-man/piston`)](https://github.com)**  
  High-speed open-source general-purpose code execution engine in Node.js/C++ with pre-built runtime packages for dozens of languages, ideal for building Replit-style playgrounds.

### Additional Strong Open-Source Options

- **[OneCompiler / Runno (`taybenlor/runno`)](https://github.com)** and **[Pyodide (`pyodide/pyodide`)](https://github.com)** for zero-backend WebAssembly (WASI) code execution directly inside the user's browser.
- **[Yjs (`yjs/yjs`)](https://github.com)** + **[Monaco Editor (`microsoft/monaco-editor`)](https://github.com)** or **[CodeMirror (`codemirror/dev`)](https://github.com)** for building custom real-time multiplayer browser code editors.
- **[Marimo (`marimo-team/marimo`)](https://github.com)** and **[JupyterHub (`jupyterhub/jupyterhub`)](https://github.com)** for reactive, collaborative, self-hosted Python data science and computational cloud notebooks.
- **[Gitea (`go-gitea/gitea`)](https://github.com)** and **[Forgejo (`forgejo/forgejo`)](https://codeberg.org)** for lightweight self-hosted Git forges pairing seamlessly with `Code-Server` and `DevPod`.
- **[Sandpack (`codesandbox/sandpack`)](https://github.com)** for CodeSandbox's open-source React component toolkit that embeds live in-browser code editors and bundlers into any documentation or learning site.

**Frameworks for building custom systems**: Combine **Coder** or **DevPod** for multi-user remote DevContainer orchestration, **OpenVSCode Server** or **Code-Server** for browser VS Code workspaces, and **Monaco Editor + Yjs + Piston** for interactive multiplayer coding sandboxes.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Self-hosted cloud IDEs (`Code-Server`, `OpenVSCode Server`, `Coder`) expose full interactive shell access over HTTP/WebSockets; always place them behind HTTPS/TLS reverse proxies, strong OIDC/SSO authentication, and strict firewall/VPN rules.
- Publicly accessible code execution engines (`Judge0`, `Piston`) must run with Linux namespaces/cgroups, seccomp filters, memory/CPU caps, and network isolation to prevent container escapes or abuse.

---

**Made for remote software engineers, open-source maintainers, educators, DevOps teams, and cloud IDE builders.**  
Let's make collaborative coding and cloud development environments more open, fast, and accessible from anywhere.
