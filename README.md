# guideos-grub-theme

Assets taken from https://github.com/diegons490/cachy-grub-theme under GPL-3.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GuideOS/guideos-grub-theme.git
   ```
2. Copy the theme folder to `/boot/grub/themes/`:
   ```bash
   sudo cp -r guideos-grub-theme /boot/grub/themes/
   ```
3. Open `/etc/default/grub` and set:
   ```
   GRUB_THEME="/boot/grub/themes/GuideOS/theme.txt"
   ```
4. Update GRUB:
   ```bash
   sudo update-grub
   ```

# Screenshot

<img width="1920" height="1080" alt="Screenshot_GuideOS 0 9 BETA_2025-12-01_19:18:35" src="https://github.com/user-attachments/assets/a05a38d1-1c22-428c-b81b-42a565075f56" />


## License

This project is licensed under the [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).
