# 🛒 Verified Scripts for Kashub

Welcome to the official repository for **verified Kashub scripts**. This collection powers the in-game marketplace for the [Kashub Mod](https://github.com/KasperStudios/kashub).

If you want your script to be accessible to all users directly inside the mod, you are in the right place!

---

## 📂 Repository Structure

The repository is organized into two main directories:

- **`manifests/`**: Contains metadata files (`.json`) describing each script.
- **`scripts/`**: Contains the actual source code files (`.kh`).

### Example Layout
```
root/
├── manifests/
│   └── auto_miner.json
└── scripts/
    └── auto_miner_v1.kh
```

---

## 🚀 How to Submit a Script

We welcome contributions from the community! To add your script to the marketplace, follow these steps:

1.  **Fork** this repository.
2.  Add your script file (`.kh`) to the `scripts/` folder.
3.  Create a manifest file (`.json`) in the `manifests/` folder (see format below).
4.  Submit a **Pull Request**.

### Manifest Format (`example.json`)
Your JSON file in `manifests/` must follow this structure:

```
{
  "name": "example script",
  "description": "Write a 'hello world!' in chat for player",
  "author": "kasperenok",
  "version": "1.0.0",
  "script_file": "example.kh",
  "category": "utility",
  "min_mod_version": "0.8.0"
}
```

*   `script_file`: Must match the filename in the `scripts/` folder exactly.
*   `category`: Suggested values: `utility`, `pvp`, `building`, `fun`.

---

## ✅ Verification Process

All submissions are manually reviewed to ensure safety and quality.
- Scripts containing malicious code or harmful actions will be rejected.
- Ensure your code is clean and readable.

---

### 🔗 Useful Links
- [Main Mod Repository](https://github.com/KasperStudios/kashub)
- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=KasperStudios.kashub-vscode)
- [Discord Community](https://discord.gg/gFeWtpEKN9)
