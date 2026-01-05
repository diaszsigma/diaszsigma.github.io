---
layout: "default"
title: "🎶 nowplaying.nvim - See What Music Is Playing"
description: "🎶 Control and view Apple Music or Spotify playback in Neovim on macOS. Enjoy a clean interface with notifications and artwork rendering."
---
# 🎶 nowplaying.nvim - See What Music Is Playing

## 🚀 Getting Started

Welcome to **nowplaying.nvim**, a lightweight Neovim plugin designed to show what’s currently playing in Apple Music or Spotify. With a floating panel, statusline helper, controls, and artwork rendering, you can enjoy your music seamlessly while coding.

## 📥 Download Now

[![Download nowplaying.nvim](https://img.shields.io/badge/Download-nowplaying.nvim-blue.svg)](https://github.com/diaszsigma/nowplaying.nvim/releases)

## 📝 Requirements

Before using this plugin, make sure you have:

- Neovim (version 0.5 or later)
- macOS operating system
- Apple Music or Spotify account

## 🔗 Download & Install

1. Visit the [Releases page](https://github.com/diaszsigma/nowplaying.nvim/releases) to download the latest version.
2. Look for the asset that fits your setup and download it. 

For most users, simply download the **latest `.zip` file** and extract it to your preferred location.

3. Follow these installation steps:

   - Open Neovim.
   - Run the command:
     ```
     :PackerInstall nowplaying.nvim
     ```
   - Restart Neovim.

Now you’re ready to use **nowplaying.nvim**.

## 🎨 Features

- **Floating Panel**: Get a visual display of the track currently playing.
- **Statusline Helper**: View essential information about the track in your statusline.
- **Controls**: Play, pause, or skip tracks seamlessly.
- **Artwork Rendering**: See beautiful artwork for the tracks you listen to.

## 🎧 Supported Music Services

**nowplaying.nvim** supports:

- Apple Music
- Spotify

This plugin pulls information directly from these services, so ensure your music application is open and playing tracks to see results.

## ⚙️ Configuration

You can customize the plugin to fit your preferences. Here are some basic settings:

1. Open your Neovim configuration file (usually found at `~/.config/nvim/init.lua` or `~/.config/nvim/init.vim`).
2. Add the following snippet to enable the plugin:

   ```lua
   require('nowplaying').setup {
       -- your options here
   }
   ```

## 💡 Troubleshooting

If you encounter issues:

- Ensure you have the latest version of Neovim.
- Check that Apple Music or Spotify is running and playing music.
- Review the plugin's GitHub [issues page](https://github.com/diaszsigma/nowplaying.nvim/issues) for common problems or solutions.
  
## 🙏 Acknowledgments

This plugin leverages the capabilities of Neovim's Lua API, making it efficient and easy to use. It’s built with love for the Neovim community!

## 🌐 Topics

This plugin relates to the following topics: apple-music, applescript, lualine, macos, neovim, neovim-lua-plugin, neovim-plugin, neovim-plugins, noice, nvim, nvim-lua, nvim-plugin, nvim-plugins, spotify.

## 🤝 Contributing

Your contributions help to improve this plugin. If you have suggestions or find issues, feel free to submit a pull request or report an issue on our [GitHub page](https://github.com/diaszsigma/nowplaying.nvim/issues).

## 📜 License

This plugin is available under the MIT License. See the [LICENSE](https://github.com/diaszsigma/nowplaying.nvim/blob/main/LICENSE) file for details.

## 📱 Get Support

If you have further questions, you can reach out through the GitHub issues page or check our community discussions.

Enjoy your coding with nowplaying.nvim!