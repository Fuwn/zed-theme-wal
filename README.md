<div align="center">
  <h1><code>zed-theme-wal</code></h1>
  
  A theme for the Zed text editor that utilises your [wal](https://github.com/dylanaraps/pywal) colour scheme

  <br>

  <img src="https://i.imgur.com/b9nMefI.png" width="90%">
</div>

# Usage

Since this theme is dynamic in nature, it can't exactly be committed to Zed's extension repository just yet due to the way extensions work.
You'll have to follow a few steps.

```bash
# Clone the repository locally
git clone https://github.com/Fuwn/zed-theme-wal.git

# Navigate into the extension folder
cd zed-theme-wal

# Generate the theme from your wal colour scheme
chmod +x ./generate_theme && ./generate_theme
```

After these steps, you'll have a fully useable Zed theme generated from your wal colour scheme ready to install.

1. Open Zed.
2. Press <kbd>Ctrl + Shift + P</kbd> to open the command palette.
3. Search for "extensions" and click on "zed: extensions".
4. Click on "Install Dev Extension", navigate to local repository copy, and select it.
5. Press <kbd>Ctrl + K</kbd>, then <kbd>Ctrl + T</kbd>, and select the "wal" theme.

You've done it! You should now see your current wal colour scheme applied to Zed.

## Updating

`zed-theme-wal`'s [`generate_theme`](./generate_theme) script is path safe, so feel free to put this in any of your background setting scripts as a hook, or even add a global
alias to it and run it after you change your wallpaper. Zed will automatically update any local themes you have installed, so you only have to go through the
above process once!

# Licence

This project is licensed with the [GNU General Public License v3.0](./LICENSE).
