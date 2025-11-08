# Solana Workshop Template (Rust & CLI)

This repository is configured as a GitHub Codespaces Template to provide you with a zero-setup development environment pre-loaded with all the necessary tools for Solana development.

No need to install Rust, the Solana CLI, or Node.js locally—everything works instantly in your browser!

---

## Tech Stack & Tools Included

| Technology | Purpose | Version Included |
| :--- | :--- | :--- |
| **Solana CLI** | The command-line tool for interacting with the Solana cluster (keygen, program deploy). | Latest Stable |
| **Rust** | The primary language for writing fast, secure Solana programs. | Latest Stable |
| **Node.js / npm** | For using Javascript/Typescript client libraries (e.g., `@solana/web3.js`). | LTS |
| **VS Code Extensions** | Pre-installed extensions for Rust development (e.g., `rust-analyzer`). | N/A |

---

## Getting Started

Follow these two simple steps to launch your pre-configured environment in the cloud:

### 1. Open in Codespace

Click the green **"Code"** button and select **"Create codespace on main"** from the dropdown menu.

Alternatively, click this badge:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/YOUR-GITHUB-ORG/solana-workshop-template)

> **Note:** GitHub will create a fresh copy of this repository in a powerful cloud machine, which might take 1–2 minutes for the initial setup and dependency installation.

### 2. Verify Your Environment

Once the VS Code editor opens in your browser, the terminal should be visible at the bottom.

Run these commands to confirm all tools are correctly installed:

```bash
# Verify the core Solana toolchain is ready
solana --version

# Verify Rust is ready for building programs
rustc --version
```

## Clean Up: Deleting Your Codespace

Your Codespace is a cloud-hosted environment. While generous usage is free for all new accounts, we recommend deleting your Codespace once you are fully finished to avoid incurring unexpected charges.

Please follow this step to stop your cloud environment.

1.  Go to your codespaces list by navigating to: [https://github.com/codespaces](https://github.com/codespaces)

2.  Locate and delete the codespace:
    * Find the Codespace named for your workshop (e.g., `solana-workshop-template...`).
    * Click the **three dots ($\dots$)** on the right side.
    * Select **Delete**.
