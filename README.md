# DuckyOne2Mini-Karabiner

Ducky One2 Mini Remapping for Karabiner Elements that emulates the TAP Layout feature in Anne Pro 2 keyboards.

## Usage

1. Verify the VendorID and the ProductID in the ducky.json matches with your keyboard's vendor and product ID. (Can be checked from the System Information app under `USB → <Keyboard Name>`).
2. Ensure the file is in the correct location `~/.config/karabiner/assets/complex_modifications/`.
3. Load the Complex modification from Karabiner Elements app.

## Normal Layout

![Normal Configuration](https://raw.githubusercontent.com/mmshivesh/DuckyOne2Mini-Karabiner/master/images/normal.png)

## Karabiner Complex Modification

1. Tapping the key will work as an arrow key (holding up to 200ms). Using it for keyboard shortcuts with any other key will let it work as the original key. Holding for longer (Default threshold 600ms) will start repeating arrow keys.

![Arrow Key mode](https://raw.githubusercontent.com/mmshivesh/DuckyOne2Mini-Karabiner/master/images/modified.png)

2. Pressing ⌘ + Esc will act like pressing ⌘ + ~ (Allowing you to cycle through application windows and going backwards in the ⌘ + Tab screen).

Not Pressed:

![Not holding command](https://raw.githubusercontent.com/mmshivesh/DuckyOne2Mini-Karabiner/master/images/notpressed.png)

⌘ Pressed:

![Holding command](https://raw.githubusercontent.com/mmshivesh/DuckyOne2Mini-Karabiner/master/images/pressed.png)
