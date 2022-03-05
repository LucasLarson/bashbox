# bashbox

A single script that gives coreutils like things written in pure `bash`.

This isnt intended to be really posix, it is missing lot of things from posix and some things behave differently.

# bashbox-create
(can be called both as ./bashbox bashbox create, ./bashbox-create or , ./bin/bashbox-create)
merge things in bin/ to one script

options (can be combined):

	bin - make unformated compilation of all stuff in bin/ (pretty fast)

	formatbin - make compilation of all stuff in bin/ (pretty slow)

	info - print info on what will be merged and how will help message look

	you can call other functions defined in bashbox-create, but they are mostly just copies of stuff in bin/ needed for merging (wc, head, tail, seq, cat)
	
# contributing
if you want contribute, **do not edit "bashbox/bxlib" file, its just automerged file, edit things in bin/.**

# thanks
in bashbox is used:

https://github.com/lijaesela/bim (unlicense)

https://github.com/dylanaraps/bareutils ((mit) bashbox is fork of this)

https://github.com/dylanaraps/pure-bash-bible (mit)

https://github.com/greymd/pure-bash-alternatives (mit)

https://github.com/catmin/purebash (unknown)

https://github.com/agriffis/pure-getopt (mit)

https://github.com/yokkidack/shaverma (mit)

and other random scripts i found on iternet and were without license:

	- curl
	
	- ord
	
	- chr
	
	- hd
	
	- tac (most of)


