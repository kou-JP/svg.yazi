# svg.yazi

Plugin for svg preview on [Yazi](https://github.com/sxyazi/yazi) using [librsvg](https://wiki.gnome.org/Projects/LibRsvg).

## Installation

```sh
# Linux/macOS
git clone https://github.com/kou-JP/svg.yazi.git ~/.config/yazi/plugins/svg.yazi

# Windows
git clone https://github.com/kou-JP/svg.yazi.git %AppData%\yazi\config\plugins\svg.yazi
```

## Usage

Add this to your `yazi.toml`:

```toml
[plugin]
prepend_previewers = [
  { name = "*.svg", exec = "svg" },
]
```

Make sure that [librsvg](https://wiki.gnome.org/Projects/LibRsvg) is installed and that `rsvg-convert` is on your `PATH`.
