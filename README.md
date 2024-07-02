# CPL Mouse Fix

This repository hosts registry modifications to enhance mouse sensitivity by disabling built-in mouse acceleration, and a corresponding uninstallation file to revert these changes. This fix is ideal for gamers seeking precise control and responsiveness during gameplay.

## Installation

### Applying the Mouse Fix

To apply the mouse sensitivity fix:

1. **Backup your registry**: Before making any changes, ensure you back up your current registry settings to avoid potential issues.

2. **Modify the registry**:
   - Open `Registry Editor` by typing `regedit` in the Run dialog (Win + R).
   - Navigate to `HKEY_CURRENT_USER\Control Panel\Mouse`.
   - Import the `install.reg` file provided in this repository.

3. **Restart your computer**: Changes will take effect after a restart.

### Uninstalling the Mouse Fix

To revert to the original mouse settings:

1. **Open `Registry Editor`** as described above.
2. **Import the `uninstall.reg` file** from this repository to restore the default settings.
3. **Restart your computer** to apply the changes.

## Usage

After applying the `install.reg` file, the mouse acceleration will be disabled, which aligns cursor movement more closely with your physical mouse movements. This adjustment can significantly improve precision in gaming. Initially, the mouse might feel slow, but as you adjust, the increased control becomes evident.

## Contributing

Contributions are welcome! If you have improvements or modifications, please fork this repository, commit your changes, and submit a pull request.

## License

This project is released under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

Thanks to the Cyberathlete Professional League's members for this mouse fix all those years ago.
