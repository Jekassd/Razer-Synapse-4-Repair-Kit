
# Razer Synapse 4 Repair Kit

🛠️ A fix for Razer Synapse 4 failing to launch on specific Windows user profiles.

This tool helps resolve issues where Synapse 4 fails to start, shows no interface, or silently crashes due to corrupted user-level data or registry misconfigurations.

---

## 📦 Contents

- `FixSynapse.cmd`  
  Cleans up local Razer config, WebView2 cache, and launches Synapse.

- `RazerProfileFix.reg`  
  Repairs registry keys related to execution, AppContainer, and compatibility.

- `README.md`  
  This file.

- `Razer_Synapse4_Repair_Kit.zip`  
  Full package for offline use.

---

## ✅ When to Use This

- Synapse 4 won't open but works on another Windows account
- You see no icon, window, or task in Task Manager
- You've reinstalled Synapse 4 and it still doesn't work
- SideBySide or .NET errors in Event Viewer

---

## 🚀 How to Use

### 1. Apply the Registry Fix

- Double-click `RazerProfileFix.reg`
- Confirm and allow registry changes
- Restart your PC

### 2. Run the Cleanup Script

- Right-click `FixSynapse.cmd` → Run as administrator
- Wait for the script to complete
- Check your desktop for `synapse_log.txt`

---

## 💬 Notes

- Works only with **Razer Synapse 4**
- Can be run multiple times safely
- No admin rights needed for the `.reg` file, but required for `.cmd`

---

## 📄 License

MIT — do whatever you want, just credit this repo if you share or build on it.

---

Made with ☕ and frustration by [Jekassd](https://github.com/Jekassd) and ChatGPT.
