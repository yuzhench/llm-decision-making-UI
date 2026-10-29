# LLM Decision Making

The app for writing your answers in the LLM Decision Making study (Harvard AI & Robotics Lab).
Available for **Mac** (macOS 11 or later, Apple silicon and Intel) and **Windows** (Windows 10 or 11, 64-bit).

- [Mac](#mac)
- [Windows](#windows)

## Mac

### Install

1. Download **[LLM-Decision-Making-mac.dmg](https://github.com/yuzhench/llm-decision-making-UI/raw/main/LLM-Decision-Making-mac.dmg)** and open it.
2. Drag **LLM Decision Making** onto the **Applications** folder.

### Open it the first time

The app is not registered with Apple, so macOS blocks it once. This is expected.

1. Open **LLM Decision Making** from Applications. macOS says it cannot verify the developer: click **Done** (not "Move to Bin").
2. Go to **System Settings → Privacy & Security**, scroll down to **Security**, and click **Open Anyway** next to "LLM Decision Making".
3. Enter your Mac password, then click **Open Anyway** again.

After this it opens like any other app. On macOS 14 or earlier you can instead right-click the app and choose **Open**.

If macOS says the app **"is damaged and can't be opened"**, run this in Terminal, then open the app again:

```
xattr -dr com.apple.quarantine "/Applications/LLM Decision Making.app"
```

## Windows

### Install

> **Use Google Chrome to download the installer.** Internet Explorer and Microsoft Edge may block the download.

1. Download **[LLM-Decision-Making-windows-setup.exe](https://github.com/yuzhench/llm-decision-making-UI/raw/main/LLM-Decision-Making-windows-setup.exe)**.
2. Double-click the downloaded file to run the installer.
3. Right click on downloaded file and select "Run as administrator".
   -> If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**.
   This appears because the app is not registered with Microsoft. It is expected.
5. Click through the installer (no administrator password needed) and click **Finish**.

If Chrome warns about the file, choose **Keep**.

After installing, open **LLM Decision Making** from the Start menu.

## Use

Log in with your study username and password, and write your answers in the app.
