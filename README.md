# NoTrace-tool
🚫 NoTrace — Secure Data Wiping Tool
SIH Problem Statement ID: 25070

🔍 Overview

NoTrace is a secure data wiping and verification tool developed for the Smart India Hackathon (SIH) Problem Statement 25070.
It ensures complete and verifiable deletion of data from storage devices, supporting both individual and enterprise-level use cases.

⚙️ Features

DoD/NIST Compliant Wiping Algorithms (multi-pass secure erase)

Cross-Platform Support – Windows, Linux, Android

Verification Reports with checksums & logs

Bulk Data Wipe Mode for enterprises

Simple & Interactive UI (Web + CLI options)

Offline Operation – No internet required for wiping

🧠 Tech Stack

Frontend: html css & js 

Backend/Core: Python / Node.js / Native CLI

Libraries: Pandas, NumPy, Scikit-learn (for data verification and logs)

Deployment: Vercel (Web Demo)

🚀 How It Works

Select the target device or file directory.

Choose a wiping algorithm (DoD, NIST, Gutmann, etc.).

Start the secure erase process.

Receive a verification report with detailed wipe logs.

📦 Project Structure
NoTrace/
├── frontend/         # React-based UI
├── core/             # Wiping engine / CLI scripts
├── reports/          # Generated reports & logs
└── README.md

📈 Purpose

This project was developed during my learning phase as part of SIH to understand secure data management, automation, and compliance with data privacy standards.

🔒 Note

This project is for educational and research purposes only.
Do not use on drives containing important or live data.

Developed by: Anand Vaidya
Live Demo: https://no-trace-tool.vercel.app/

SIH Problem Statement: 25070
