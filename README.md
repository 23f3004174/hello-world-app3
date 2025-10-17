# Hello World! Flask App

## Overview
A minimal Flask web app that serves a single route (/) which displays “Hello World!” in a simple HTML page. This project is packaged as a single-file app for easy running and portability.

## Setup
- Requirements:
  - Python 3.8+ recommended
  - pip

- Install dependencies:
  - Option A: User environment
    - pip install flask
  - Option B: Virtual environment (recommended)
    - python -m venv .venv
    - On Windows: .venv\Scripts\activate
      On macOS/Linux: source .venv/bin/activate
    - pip install flask

## Usage
1. Start the server:
   - python index.html
   - Optional: choose a port
     - On macOS/Linux: PORT=8000 python index.html
     - On Windows (Powershell): $env:PORT=8000; python index.html

2. Open your browser:
   - http://127.0.0.1:5000/ (or the port you set)

You should see a page showing: Hello World!

## Improvements in Round 2
- Consolidated into a single-file app (index.html) for zero-config startup.
- Added responsive, minimal CSS for a cleaner “Hello World!” display.
- Allowed port override via PORT environment variable for easier deployment.
- Clarified setup/usage steps for a faster run experience.