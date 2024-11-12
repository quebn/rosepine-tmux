# Rose Pine Theme for Tmux.

1.
![screenshot-20241113-000336](https://github.com/user-attachments/assets/3a6c6d04-1194-49b7-8762-304d9f5a146a)
2.
![screenshot-20241113-000309](https://github.com/user-attachments/assets/714786e8-b0d4-42c6-a772-dc541c88eb5e)


> [!NOTE]
> This theme uses [NerdFonts](https://www.nerdfonts.com/font-downloads) by default. I highly recommend that you install and set it as a terminal font.

> [!IMPORTANT]
> This theme was made with only transparent terminal in mind.

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
