# tmux reference guide

## Outside tmux

| Command                     | Description                                |
|-----------------------------|--------------------------------------------|
| `tmux new`                  | Start a new session                        |
| `tmux new -s name`          | Creates a new session with the name `name` |
| `tmux kill-session -t name` | Kills session `name`                       |
| `tmux ls`                   | List all sessions                          |
| `tmux a`                    | Attach to last session                     |
| `tmux a -t name`            | Attach to session `name`                   |
| `tmux info`                 | Show every session, window, pane, etc      |

## Inside tmux

- **Windows**: Only one may be displayed at a time.
- **Panes**: Belongs to windows, many may be visible at a time.

### Windows

| Command      | Description                   |
|--------------|-------------------------------|
| `C-b c`      | Create a window               |
| `C-b ,`      | Rename the current window     |
| `C-b &`      | Close the current window      |
| `C-b p`      | Switch to the previous window |
| `C-b n`      | Switch to the next window     |
| `C-b 0 .. 9` | Select window by number       |

### Panes

| Command            | Description                          |
|--------------------|--------------------------------------|
| `C-b %`            | Split pane vertically                |
| `C-b "`            | Split pane horizontally              |
| `C-b {`            | Move pane left                       |
| `C-b }`            | Move pane right                      |
| `C-b ↑/↓/←/→`      | Switch to pane in relevant direction |
| `C-b <SPC>`        | Switch between pane layouts          |
| `C-b o`            | Switch to next pane                  |
| `C-b q`            | Show pane numbers                    |
| `C-b q 0 .. 9`     | Select pane by number                |
| `C-b !`            | Convert pane into a window           |
| `C-b-↑` or `C-b-↓` | Resize current pane height           |
| `C-b-←` or `C-b-→` | Resize current pane width            |
| `C-b x`            | Close current pane                   |
