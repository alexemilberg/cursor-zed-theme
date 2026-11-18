# Curzed

A best-effort port of Cursor Dark and Cursor Light to a Zed theme. Credit to Ryo Lu for the awesome original theme.

Zed colors languages differently than Cursor, so some tokens cannot match exactly. The palette follows his themes as closely as it can.

## Install in Zed

1. Open the command palette and run `zed: extensions`.
2. Choose **Install Dev Extension**.
3. Select this folder (`cursor-zed-theme`).

Then open the theme picker and choose **Curzed Dark** or **Curzed Light**.

To follow the system appearance, the same way Cursor does with `window.autoDetectColorScheme`, add this to Zed settings:

```json
{
  "theme": {
    "mode": "system",
    "light": "Curzed Light",
    "dark": "Curzed Dark"
  }
}
```
