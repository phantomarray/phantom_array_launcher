# Phantom Array Launcher

<p align="center">
  <img src="docs/images/banner.webp" alt="Phantom Array Launcher" width="900">
</p>

<p align="center">
  <strong>Every profile. A unique destiny.</strong>
</p>

<p align="center">
  A portable Windows desktop launcher for managing isolated browser environments,
  customizable profiles, fingerprint configurations, and synchronized workflows.
</p>

<p align="center">
  <a href="https://github.com/phantomarray/phantom_array_launcher/releases">Download</a>
  ·
  <a href="https://github.com/phantomarray/phantom_array_launcher/releases">Releases</a>
</p>

---

# Overview

**Phantom Array Launcher** is a portable Windows application designed for creating,
managing, and launching independent browser environments from a single workspace.

Each profile maintains its own isolated configuration:

- Browser data
- Cookies and local storage
- Proxy configuration
- Fingerprint configuration
- Screen and window parameters
- Runtime settings

The launcher is distributed as a standalone executable.

> **No installation. No mandatory account. One launcher. Multiple environments.**

---

# Screenshots

<p align="center">
  <img src="docs/images/dashboard.png" width="45%" alt="Dashboard">
  <img src="docs/images/profile-manager.png" width="45%" alt="Profile Manager">
</p>

<p align="center">
  <img src="docs/images/fingerprint-test-1.PNG" width="45%" alt="Fingerprint Environment">
  <img src="docs/images/sync-action.png" width="45%" alt="Synchronizer Action">
</p>

---

# Features

## Profile Management

Manage multiple independent browser environments.

Features:

- Create profiles
- Edit profile configuration
- Duplicate profiles
- Delete profiles
- Launch profiles independently
- Persistent local profile data
- Portable profile management

---

# Fingerprint Environment

Phantom Array provides a configurable browser environment layer.

Supported components:

- Canvas configuration
- ClientRects configuration
- Screen parameters
- Window parameters
- Browser environment settings
- Reusable fingerprint profiles

Fingerprint configurations can be stored,
managed, and applied across profiles.

---

# Custom Screen & Window Engine

Advanced control over browser-visible screen and window parameters.

Supported configuration:

- Screen width and height
- Available screen dimensions
- Window dimensions
- Browser viewport dimensions
- Color depth
- Pixel depth
- Platform-specific geometry handling

Each profile can maintain independent screen and window settings.

---

# ShadowShock Engine

ShadowShock is an integrated environment processing layer
for advanced profile customization.

Capabilities:

- Runtime environment processing
- Modular environment adjustments
- Profile-level configuration handling
- Integrated launcher workflow

---

# Synchronizer Action

Synchronizer Action provides coordinated actions
across managed environments.

Capabilities:

- Action synchronization
- Multi-profile operations
- Workflow coordination
- Centralized action management

Designed for managing repeated operations
across multiple profiles.

---

# Proxy Management

Configure proxy environments independently per profile.

Supported:

- HTTP proxies
- SOCKS5 proxies
- Proxy authentication
- Connectivity testing
- Geographic information
- Cached proxy validation results

Proxy results are cached to reduce repeated checks
and improve launch responsiveness.

---

# Portable Architecture

Phantom Array Launcher is designed around separated modules:

```
                    Phantom Array Launcher

                            UI
                             |
                    Runtime Manager
                             |
        -----------------------------------------
        |                 |                     |
 Fingerprint        Screen Engine       Synchronizer
        |
 Profile Storage
        |
 Runtime Configuration
```

Each component is separated to keep profiles,
configuration, and runtime data independently manageable.

---

# Portable by Design

Phantom Array Launcher runs as a portable Windows executable.

Advantages:

- No installer required
- No setup wizard
- Easy deployment
- Portable runtime directory
- Simple backup and migration

Download the executable, run it,
and start managing browser environments.

---

# Getting Started

## 1. Download

Get the latest Windows x64 build from GitHub Releases:

**Download Phantom Array Launcher**

---

## 2. WebView2 Runtime

Phantom Array Launcher requires:

**Microsoft Edge WebView2 Runtime (Evergreen)**

Most supported Windows systems already include it.

If missing, install:

**Microsoft WebView2 Runtime — Windows x64**

After installation, restart Phantom Array Launcher.

---

## 3. Run

Launch:

```text
Phantom-Array-Launcher-portable-win-x64.exe
```

---

# Roadmap

Completed:

- Profile management
- Fingerprint environment
- Proxy management
- Custom screen/window engine
- ShadowShock engine
- Synchronizer Action
- Runtime improvements

Future improvements:

- Additional environment modules
- Extended profile management
- More workflow capabilities
- Further runtime optimizations

---

# License

See repository license information.
