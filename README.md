# Phantom Array Launcher

<p align="center">
  <strong>Every profile. A unique destiny.</strong>
</p>

<p align="center">
  A portable Windows desktop launcher for managing isolated browser profiles with flexible environment and fingerprint customization.
</p>

<p align="center">
  <a href="https://github.com/phantomarray/phantom_array_launcher/releases/tag/v1.0.0">Download v1.0.0</a>
  ·
  <a href="https://github.com/phantomarray/phantom_array_launcher/releases">All Releases</a>
</p>

---

## Overview

**Phantom Array Launcher** is a portable Windows application built for users who need to create, manage, and launch separate browser profiles from one place.

Each profile can maintain its own browser environment, fingerprint configuration, proxy settings, cookies, local data, and screen/window parameters.

The launcher is distributed as a standalone executable — **no application installer is required**.

> **No installation. No mandatory account. One launcher. Multiple environments.**

---

## Screenshots

<p align="center">
  <img src="docs/images/fingerprint-test-1.PNG" alt="Phantom Array Launcher">
</p>

<p align="center">
  <img src="docs/images/fingerprint-test-2.PNG" alt="Phantom Array Launcher">
</p>

<p align="center">
  <img src="docs/images/fingerprint-test-3.PNG" alt="Phantom Array Launcher">
</p>

---

## Features

### Profile Management

Manage multiple browser profiles from a single workspace.

- Create and manage independent profiles
- Edit profile configuration
- Duplicate profiles
- Delete profiles
- Launch profiles independently
- Persistent local profile data

### Browser Environment Customization

Configure browser-environment parameters on a per-profile basis.

Supported areas include:

- Fingerprint configuration
- Canvas
- ClientRects
- Screen configuration
- Window configuration
- Proxy configuration
- Browser profile data

### Fingerprint Library

Create and reuse fingerprint configurations across profiles.

The Fingerprint Library supports importing fingerprint configuration data from files and applying reusable configurations to browser profiles.

### Proxy Support

Configure proxies independently for browser profiles.

The launcher supports:

- HTTP proxies
- SOCKS5 proxies
- Proxy authentication
- Proxy connectivity testing
- Geographic information
- Cached proxy test results

Proxy test results are cached to reduce unnecessary repeated checks while keeping profile launches responsive.

### Screen & Window Configuration

Customize screen and browser-window parameters for individual profiles.

This includes configurable values such as:

- Screen width and height
- Available screen dimensions
- Color depth
- Pixel depth
- Window width and height
- Browser viewport dimensions

### Portable by Design

Phantom Array Launcher is delivered as a portable Windows executable.

**No application installer. No setup wizard.**

Download the executable, run it, and start using the launcher.

---

## Getting Started

### 1. Download

Get the latest Windows x64 build from the GitHub Releases page:

**[Download Phantom Array Launcher v1.0.0](https://github.com/phantomarray/phantom_array_launcher/releases/tag/v1.0.0)**

### 2. WebView2 Runtime

Phantom Array Launcher requires **Microsoft Edge WebView2 Runtime (Evergreen)**.

Most supported Windows systems already have WebView2 Runtime installed. If it is missing, install the official Microsoft WebView2 Runtime:

**[Download WebView2 Runtime — Windows x64](https://go.microsoft.com/fwlink/p/?LinkId=2124703)**

This is Microsoft's official Evergreen Standalone Installer for Windows x64.

After installation, run the Phantom Array Launcher executable again.

### 3. Run

Launch:

```text
Phantom-Array-Launcher-portable-win-x64.exe
