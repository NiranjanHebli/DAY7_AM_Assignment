

# DAY 7 AM Assignment
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## Overview
This folder contains the Day 7 AM assignment script `onboard.py` and accompanying files used to verify environment setup for the onboarding exercise.

## Prerequisites
- Python 3.x
- (Recommended) Use a virtual environment to avoid global package changes.

## 1. Create & activate the venv

### macOS / Linux
```bash
python3 -m venv onboarding_env
source onboarding_env/bin/activate
```

### Windows (PowerShell)
```powershell
onboarding_env\Scripts\Activate.ps1
```

### Windows (Command Prompt)
```cmd
onboarding_env\Scripts\activate
```

## 2. Install packages
From the repository root (this project's `requirements.txt`):

```bash
pip install -r requirements.txt
```

## 3. Run the check

```bash
python3 onboard.py
```

## Notes
- The `onboard.py` script performs environment and dependency checks used for the assignment.
- If you activated a venv inside this folder, remember to deactivate it when finished with `deactivate`.
