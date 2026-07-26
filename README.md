# EdgeNest — Client Releases

EdgeNest 客户端的下载与自动更新信道，覆盖 macOS / Windows / Android 三端安装包；iOS 版通过 TestFlight 分发。面向 OpenWrt 系路由器（如 iStoreOS）的版本是独立产品，不在本仓库分发，说明见文末。

This repository is the download and auto-update channel for the EdgeNest client. It hosts installers for macOS, Windows, and Android; the iOS build is distributed through TestFlight. The build for OpenWrt-family routers (such as iStoreOS) is a separate product and is not distributed here — see the note at the end.

## macOS

**系统要求**：macOS 13（Ventura）或更高版本，同时支持 Apple 芯片与 Intel 芯片的 Mac。

**下载**：前往 [Releases](../../releases/latest)，下载最新的 `EdgeNest-<版本>.dmg`。

**安装**：打开 dmg，把 EdgeNest 拖进「应用程序」文件夹即可。安装包已经过 Apple 公证，双击正常打开，不需要额外的确认步骤。

**升级**：应用会自动检查更新（基于 Sparkle），发现新版本会提示下载安装；也可以在 设置 → 关于 → 检查更新 手动检查。

---

**System requirements**: macOS 13 (Ventura) or later; supports both Apple silicon and Intel Macs.

**Download**: Get the latest `EdgeNest-<version>.dmg` from [Releases](../../releases/latest).

**Install**: Open the dmg and drag EdgeNest into Applications. The installer is notarized by Apple, so it opens normally with no extra confirmation.

**Update**: The app checks for updates automatically via Sparkle and prompts you when a new version is available; you can also check manually from Settings → About → Check for updates.

## Windows

**系统要求**：Windows 10 或更高版本，64 位系统；在 ARM64 版 Windows 上通过系统自带的 x64 兼容层运行。

**下载**：前往 [Releases](../../releases/latest)，下载最新的 `EdgeNest-<版本>-x64-setup.exe`。

**安装**：运行安装程序并按提示完成安装（需要一次管理员权限确认）。

**首次连接**：点击「连接」时会额外弹出一次 Windows 的用户账户控制（UAC）确认，用于安装后台服务；同意后即可连接，之后再连接不会重复询问。

**升级**：应用内可以直接检查并安装更新——检测到新版本后会下载安装包、校验完整性并自动运行，流程与首次安装一致。

---

**System requirements**: Windows 10 or later, 64-bit; runs on ARM64 Windows through the built-in x64 compatibility layer.

**Download**: Get the latest `EdgeNest-<version>-x64-setup.exe` from [Releases](../../releases/latest).

**Install**: Run the installer and follow the prompts (one administrator confirmation is required).

**First connection**: Clicking "Connect" triggers one extra Windows User Account Control (UAC) prompt to install the background service; approve it once, and later connections won't ask again.

**Update**: The app can check for and install updates itself — it downloads the installer, verifies its integrity, and runs it automatically, following the same steps as a fresh install.

## Android

**系统要求**：Android 8.0（API 26）或更高版本。

**下载**：前往 [Releases](../../releases/latest)，下载最新的 `EdgeNest-<版本>.apk`。

**安装**：需要在系统设置中允许「安装未知来源应用」，下载完成后点击 APK 文件手动安装。

**升级**：应用内检查更新会打开发布页面，需要手动下载新版本 APK 并安装，步骤与首次安装相同。

---

**System requirements**: Android 8.0 (API level 26) or later.

**Download**: Get the latest `EdgeNest-<version>.apk` from [Releases](../../releases/latest).

**Install**: Allow "Install unknown apps" in system settings, then tap the downloaded APK to install it.

**Update**: The in-app update check opens the release page in your browser; download the new APK and install it manually, the same way as the first install.

## iOS

**分发方式**：TestFlight 公开测试链接，安装包不在本仓库分发。

**安装**：先从 App Store 安装 TestFlight，然后打开 [TestFlight 链接](https://beta.itunes.apple.com/v1/app/6788733628) 加入测试，即可安装 EdgeNest。

**升级**：新版本发布后 TestFlight 会提示更新，也可以随时打开 TestFlight 手动检查。

---

**Distribution**: A public TestFlight link; no installer is hosted in this repository.

**Install**: Install TestFlight from the App Store first, then open the [TestFlight link](https://beta.itunes.apple.com/v1/app/6788733628) to join the beta and install EdgeNest.

**Update**: TestFlight notifies you when a new build is available; you can also open TestFlight any time to check manually.

## 路由器版 / Router build

面向 OpenWrt 系路由器（如 iStoreOS）的版本是独立产品，通过路由器管理面板自带的升级功能分发，安装包不在本仓库提供。

The build for OpenWrt-family routers (such as iStoreOS) is a separate product, distributed through the router's own management-panel update feature; installers are not hosted in this repository.
