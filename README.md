# Vina Tsama downloads

Installers for **Vina Tsama**, an app for a food business: orders, deliveries, payments, invoices and receipts,
expenses and reports. It runs on your own computer and opens in your web browser. Your data stays on that
computer.

**Download and update page: https://ttemu34.github.io/vina-tsama-releases/** (the easiest place to start).

## Install

1. Open [the latest release](../../releases/latest) and download the file for your computer:
   `…-windows.zip`, `…-mac.zip` or `…-linux.zip`.
2. Unzip it.
3. Start the installer:
   - **Windows:** double-click **Install Vina Tsama**. If Windows shows "Windows protected your PC", click
     **More info**, then **Run anyway**.
   - **Mac:** double-click **Install Vina Tsama**. macOS says it "could not verify" it: click **Done**, open
     **System Settings → Privacy & Security**, scroll down to Security and click **Open Anyway** (only the
     first time).
   - **Linux:** right-click **Install Vina Tsama.sh** and choose **Run as a Program**.

No administrator password is needed. The first install downloads what it needs (a few hundred MB, a few
minutes). Vina Tsama then opens in your browser with a short Welcome setup. After that, open it from
Applications or the Start menu; it starts straight away, without internet.

## Update

Run a newer installer the same way. Your orders, customers and expenses are kept, and a backup is made before
anything changes. Uninstalling never deletes your data.

## Check a download

Each release has a `SHA256SUMS.txt`. To check a file, compare its SHA-256 with the line for it:

- Mac / Linux: `shasum -a 256 Vina-Tsama-*-mac.zip`
- Windows (PowerShell): `Get-FileHash .\Vina-Tsama-*-windows.zip`

This repository holds only the released installers. Each one contains the app as it is installed: its Python
code, its built screens and the installer scripts.
