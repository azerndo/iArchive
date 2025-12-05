# iArchive

![iArchive Logo](assets/logo.png)

**iArchive** is a minimalist, modern file archiver built with Python and PyQt6. It provides a clean interface for creating, extracting, and managing archive files with a focus on user experience and macOS aesthetics.

## Features

* **🎨 Minimalist UI:** A clean, Brown & Orange "Warm Modern" theme.
* **🖱️ Drag & Drop:** Drag files directly from your file manager to archive them.
* **📂 Format Support:** * **Create:** Zip, Tar, Gzip, Bzip2, Xz.
    * **Extract:** Zip, Tar, Gzip, Bzip2, Xz, 7z*, Rar*.
* **🔒 Security:** Create password-protected Zip files (AES encryption compatible).
* **🛠️ Manage Archives:** Inspect archive contents, verify SHA-256 checksums, append files, and delete entries (Tar only).
* **🍎 Native Feel:** Optimized for macOS with native file dialogs and system tool integration.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/iarchive.git](https://github.com/yourusername/iarchive.git)
    cd iarchive
    ```

2.  **Create a virtual environment (Recommended):**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the application from source:

```bash
python3 src/main.py
