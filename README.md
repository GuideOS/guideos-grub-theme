# guideos-grub-theme

Assets taken from https://github.com/diegons490/cachy-grub-theme under GPL-3.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/guideos-grub-theme.git
   ```
2. Copy the theme folder to `/boot/grub/themes/`:
   ```bash
   sudo cp -r guideos-grub-theme /boot/grub/themes/
   ```
3. Open `/etc/default/grub` and set:
   ```
   GRUB_THEME="/boot/grub/themes/guideos-grub-theme/theme.txt"
   ```
4. Update GRUB:
   ```bash
   sudo update-grub
   ```

## Screenshot

![alt text](Screenshot.png)

## License

This project is licensed under the [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).
