# LLM Decision Making (Mac)

The app for writing your answers in the LLM Decision Making study (Harvard AI & Robotics Lab).
Works on macOS 11 or later, on Apple silicon (M1–M4) and Intel Macs.

## Install

1. Download **[LLM-Decision-Making-mac.dmg](https://github.com/yuzhench/llm-decision-making-UI/raw/main/LLM-Decision-Making-mac.dmg)** and open it.
2. Drag **LLM Decision Making** onto the **Applications** folder.

## Open it the first time

The app is not registered with Apple, so macOS blocks it once. This is expected.

1. Open **LLM Decision Making** from Applications. macOS says it cannot verify the developer: click **Done** (not "Move to Bin").
2. Go to **System Settings → Privacy & Security**, scroll down to **Security**, and click **Open Anyway** next to "LLM Decision Making".
3. Enter your Mac password, then click **Open Anyway** again.

After this it opens like any other app. On macOS 14 or earlier you can instead right-click the app and choose **Open**.

If macOS says the app **"is damaged and can't be opened"**, run this in Terminal, then open the app again:

```
xattr -dr com.apple.quarantine "/Applications/LLM Decision Making.app"
```

## Use

Log in with your study username and password, and write your answers in the app.
