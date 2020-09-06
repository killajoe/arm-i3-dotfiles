# arm-i3-dotfiles

# Setup locale and keymaps:

`localectl --no-convert set-x11-keymap de` # for x11 keymap

`echo LANG=de_DE.UTF-8 > /etc/locale.conf`

`nano /etc/locale.gen`

uncomment:

de_DE.UTF-8 UTF-8

de_DE ISO-8859-1

de_DE@euro ISO-8859-15

`locale-gen`

`echo KEYMAP=de > /etc/vconsole.conf`

`echo FONT=lat9w-16 >> /etc/vconsole.conf`

