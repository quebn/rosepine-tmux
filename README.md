# Rose Pine Theme for Tmux.

> [!NOTE]
> This theme uses [NerdFonts](https://www.nerdfonts.com/font-downloads) by default. I highly recommend that you install and set it as a terminal font.

> [!IMPORTANT]
> This theme was made with only transparent terminal in mind.

## Screenshots

![screenshot-20241113-000309](https://github.com/user-attachments/assets/e81b2b44-078c-45a1-b87c-ed2778ddb64b)

![screenshot-20241113-000336](https://github.com/user-attachments/assets/d503d12b-7085-400b-a9b1-4d55894fce4e)

## Usage

1. Install [TPM](https://github.com/tmux-plugins/tpm)
<br>

2. Add the following lines to `~/.tmux.conf` or in `~/.config/tmux/tmux.conf` file.
``` bash
set -g @plugin 'quebn/rosepine-tmux'
# ... alongside
set -g @plugin 'tmux-plugins/tpm'
# To update plugin for future revisions or bug fixes, do the "Prefix + U" keycombo

# Set your preferred variant.
set -g @rose_pine_variant 'main' # Options are 'main', 'moon' or 'dawn'
```
<br>
3. restart tmux session or update within a session using <kbd> prefix + I </kbd> to install or <kbd> prefix + U </kbd> to update your configuration.

## Thanks to.
- [RosePine Tmux](https://github.com/rose-pine/tmux) for the reference.
