# hue

A script to tint your screen with a variety of colors using `xrandr`, `xgamma`, and `fzf`.

## Features

- Select from a list of pre-defined colors, including Barbie Pink, Gameboy Green, and more.
- Easily toggle between different tints or reset your screen back to normal with a simple selection.
- Uses `fzf` for a user-friendly color selection menu.

## Dependencies

```
xrandr
xgamma
fzf
```

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/furycd001/hue.git
    cd hue
    ```

2. **Make the Script Executable**:
    ```bash
    chmod +x hue
    ```

3. **Move the Script to a Directory in Your PATH**:
    ```bash
    mv hue.sh ~/.local/bin/hue
    ```

    **Please ensure `~/.local/bin` is in your `PATH`. If not, add the following line to your `~/.bashrc` or `~/.zshrc` and reload the shell:**
    ```bash
    export PATH=$PATH:~/.local/bin
    ```

## Usage

1. **Run the Script**:
    ```bash
    hue
    ```

2. **Select a Color**:
    Use the `fzf` menu to choose your desired screen tint. You can also select "Reset to Normal" to revert your screen back to its original colors.

## Example Colors

- **Barbie Pink**: `#E0218A`
- **Lipstick Pink**: `#C48793`
- **Pastal Pink Drk**: `#FFB2B3`
- **Dark Redd**: `#C13B3A`
- **LightRed**: `#E54865`
- **Samantha**: `#E5B680`
- **Arc Dark**: `#272B35`
- **Dark Purple**: `#525466`
- **Peach**: `#E16E79`
- **Skin**: `#F6B7AB`
- **Orange**: `#EE7A63`
- **Gameboy**: `#9bbc0f`
- **8bit**: `#b9bbb6`
