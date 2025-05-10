##                                                                                
Patch Management Dashboard

A WINDOWS desktop and API-based tool that scans installed applications, checks for available updates, and manages devices remotely via SSH — with a modern PyQt6 frontend and FastAPI backend.



Features

🔐 Admin login and registration

📦 View installed applications and available updates

🚀 Trigger updates for individual or all apps

🖥️ SSH into remote devices and scan/update them

📊 PyQt6 dashboard with real-time UI feedback

⚙️ Cross-platform support (Windows, macOS, Linux)

Quick Start

Double-click setup.bat

This will:

1. Create a virtual environment

2. Install required Python libraries

3. Launch both the API server and frontend dashboard

Setup Environment Variables:

cp .env.example .env

Edit it to match your environment:

DATABASE_URL=mysql+pymysql://root:yourpassword@localhost/Patch_Management
SECRET_KEY=supersecretkey

ALGORITHM=HS256

Requirements

Python 3.9 or higher

MySQL server with a Patch_Management database

winget (Windows), brew (macOS), or apt (Linux) for update detection

git, pip, and virtualenv installed


![new architecture](https://github.com/user-attachments/assets/eaee7273-597b-4e93-8aa0-40337bbcac20)

