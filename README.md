## Poly light GRUB theme

![](https://i.imgur.com/XitFbtv.gif)

### Installation

With single command line :

`wget https://github.com/Philippe734/poly-light-grub2-theme/archive/master.zip && unzip master.zip && rm master.zip && sudo mkdir -p /boot/grub/themes && sudo mv poly-light-grub2-theme-master /boot/grub/themes/poly-light && echo "GRUB_THEME=/boot/grub/themes/poly-light/theme.txt" | sudo tee -a /etc/default/grub && sudo update-grub`

Or step by step :
1. Get theme archive: `wget https://github.com/Philippe734/poly-light-grub2-theme/archive/master.zip`
2. Unpack theme: `unzip master.zip`
3. Remove theme archive: `rm master.zip`
4. Create GRUB themes directory: `sudo mkdir -p /boot/grub/themes`
5. Move theme to GRUB themes directory: `sudo mv poly-light-grub2-theme-master /boot/grub/themes/poly-light`
6. Set `GRUB_THEME=/boot/grub/themes/poly-light/theme.txt` in GRUB config: `sudo nano /etc/default/grub`
7. Update GRUB: `sudo update-grub`
