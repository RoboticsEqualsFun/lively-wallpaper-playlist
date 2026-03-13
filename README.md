# Lively Wallpaper Playlist

A lightweight utility that automatically cycles through your saved Lively wallpapers and assigns random wallpapers to each monitor at a configurable interval. It is currently in a very unstable and buggy alpha release.

## 📥 Download

Download the latest installer from the **[Releases page](https://github.com/followedmefully/Lively-Wallpaper-Playlist/releases/tag/v0.4)** and run the `.exe` installer.

## ⚙ Requirements

- Lively Wallpaper installed
- Windows 10 or newer

## 🚀 Installation

1. Download the installer.
2. If it says lively could not be found, it is one of two reasons:
  1. It was installed from microsoft store
  2. It was not installed in the default folder
If it says that, then just find the location lively was isntalled, usually `%LocalAppData%\\Packages\\12030rocksdanister.LivelyWallpaper_97hta09mmv6hy\\LocalCache\\Local`
4. Run the installer and follow the instructions. (Note: windows will try blocking the program since it uses a python executable. Just lick more info, annd then press run anyway.)
5. When it asks for the monitor numbers just look at your lively wallpaper monitors and copy that.
6. When it asks for the the path that contains your Lively wallpapers go to lively and go to Settings → General → click **Wallpaper Directory** and use that path.   
## 🧠 Configuration

After installation, open the install folder and edit `config.json`.  

Settings:

- **wallpaper_folder**  
  The folder containing your Lively wallpapers.  
  This must point to Lively’s saved wallpaper folder.

  In Lively:  
  Settings → General → click **Wallpaper Directory** and copy that path.  
  **Important:** The folder shown by Lively is **not** the final folder. After copying it, you must add `\SaveData\wptmp`.

- **delay_seconds**  
  How often wallpapers change (in seconds).

- **monitors**  
  Monitor numbers matching Lively monitor numbering (e.g., `1,2`).

- **lively_path**  
  Path to `Lively.exe`. Usually does not need changing.

## Features

- Automatically cycles through saved Lively wallpapers  
- Supports multiple monitors  
- Configurable change interval  
- Lightweight background utility

## 🧩 Planned Features

- Make the launcher support more devices and be more intuitive
- Add a custom settings window instead of manually editing the config file
- Automatic detection of Lively Wallpaper’s install location
- Optionally allow selecting which wallpapers are included
