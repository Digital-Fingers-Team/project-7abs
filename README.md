# Project Setup Guide

## Installation

1. Install Python 3.9 or higher
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```
3. Install GTK+ for Windows (required for PDF generation):
   - Download and install GTK+ from [GTK+ for Windows Runtime Environment Installer](https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases)
   - Choose the 64-bit version if you're using 64-bit Python, otherwise choose the 32-bit version
   - After installation, restart your computer

## Running the Application

```
python app.py
```

The application will be available at http://localhost:5000

## Troubleshooting

If you encounter issues with PDF generation, ensure that:

1. GTK+ is properly installed
2. The GTK+ bin directory is in your PATH environment variable
3. You've restarted your computer after installing GTK+

If the issue persists, you can still use the application without PDF generation functionality.