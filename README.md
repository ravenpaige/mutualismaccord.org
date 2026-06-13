# Mutualism Accord (`mutualismaccord.org`)

> A universal, open-source protocol and policy framework to dismantle the digital oligarchy through local-first autonomy and absolute agent loyalty.

The Mutualism Accord defines a technical standard that separates advanced computing and autonomous AI agents from centralized corporate cloud monopolies. This repository serves as the official website codebase, hosting the digital sovereignty manifesto, technical specifications, and developer documentation.

---

## 🛠️ Project Structure

This website is built using **Hugo** (a fast static site generator) paired with an **Obsidian** workflow for seamless documentation updates.

*   `content/posts/` — Contains the markdown files for the Executive Brief, Manifesto, and Technical Specs.
*   `.obsidian/` — Project configuration folder allowing you to write, link, and visualize the documentation graph directly in Obsidian before compiling.
*   `themes/` — Houses the responsive, minimalist CSS layout optimized for fast page loads and high scannability.
*   `public/` — The compiled static production build ready for deployment.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have [Hugo Extended](https://gohugo.io) installed on your local machine.

### Installation
1. Clone this repository to your local device:
   ```bash
   git clone https://github.com
   cd mutualismaccord.org
   ```

2. Initialize and update any theme submodules:
   ```bash
   git submodule update --init --recursive
   ```

3. Launch the local development server:
   ```bash
   hugo server -D
   ```
4. Open your browser and navigate to `http://localhost:1313` to view the local site.

---

## 📜 Core Technical Specifications Included

This documentation hub covers the foundational implementation blueprints for engineering Accord-compliant software systems:

1. **System Prompt Blueprint (v1.0.0)**: Hard-coded constraints forcing LLM runtimes to prioritize edge execution over remote corporate API calls.
2. **Anti-Manipulation Protocol**: Algorithmic defense rules designed to make agents block external monetization loops, targeted ads, or third-party optimization metrics.
3. **Open Interoperability Standard**: Developer instructions for leveraging vendor-neutral connection schemas (like the Model Context Protocol) to bypass platform lock-in.

---

## 🤝 How to Contribute

We welcome contributions from engineers, policy writers, and digital rights advocates.

1. **Review the Specifications**: Read through the current architectural drafts in the `content/posts/` folder.
2. **Submit an Issue**: Flag bugs, suggest prompt engineering enhancements, or propose new framework modules.
3. **Open a Pull Request**: 
   * Fork the repository.
   * Create your feature branch (`git checkout -b feature/AmazingFeature`).
   * Commit your changes using descriptive commit messages (`git commit -m 'Add edge-execution test parameters'`).
   * Push to the branch (`git push origin feature/AmazingFeature`) and open a PR.

---

## ⚖️ Licensing

This project is licensed under an open-source framework dedicated to public benefit, preventing the commercial monopolization or proprietary enclosure of its core protocols.
