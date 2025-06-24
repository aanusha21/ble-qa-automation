import os
import zipfile

# Create a directory for the project
project_dir = "ble_qa_automation"
os.makedirs(project_dir, exist_ok=True)

# Create a README.md file with project description
readme_content = """
# BLE QA Automation

This repository contains test automation scripts for Bluetooth QA projects. The goal is to provide a set of tools and scripts to automate the testing of Bluetooth Low Energy (BLE) devices.

## Project Structure
- `ble_test.py`: Sample Python script for BLE scanning.
- `.gitignore`: Git ignore file to exclude unnecessary files.
- `README.md`: Project description and setup instructions.

## Getting Started
1. Clone the repository:    
```bash
git clone https://github.com/your-username/ble-qa-project.git
cd ble-qa-project
2.Set Up a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
pip install bleak
4. Run the BLE Scanner
python ble_test.py

**##Requirements**
Python 3.7+
Bluetooth adapter (built-in or USB dongle)
bleak Python library
