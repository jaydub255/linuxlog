## very preliminary, not to be c/p'ed directly

### Installing current manjaro-xfce
did that on 16.06.1

#### first step post installation
- run

		# pacman-mirrors -i
... to get a faster mirrorlist 

#### get updates (if applicable) and upgrade shell

	# pacman -Syu && pacman -S grml-zsh-config zsh && chsh

#### language support
- imho done best by gui (via manjaro settings)

#### get additional packages
- powerful desktop system with Virtualbox (LTS-kernel!), scanner/printer support, photo editing workflow with calibrated display (and some fancy extra stuff)

		# pacman -S darktable dropbox freemind texstudio texlive-most virtualbox virtualbox-dkms-manjaro virtualbox-guest-iso linux44-virtualbox-host-modules simple-scan argyllcms displaycal hugin luminancehdr imagemagick truecrypt rapid-photo-downloader remarkable

- personal netbook edition

		# pacman -S truecrypt rapid-photo-downloader texstudio texlive-most