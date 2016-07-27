### terminal fun stuff

- get package list line from file and hand it to pacman for installation 
(heavily relies on my choice of zsh as a shell since this package is the 
determining factor for grep)

		# cat /path/to/packagelist | grep zsh | xargs sudo pacman -S

