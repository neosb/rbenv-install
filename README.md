rbenv-install
=============

*I heard you like inception, so I made softtware which installs software which installs software.*

rbenv-install is a bash script for maintaning your rbenv installation

	usage: rbenv-install [OPTION...]

	you can pass this options:
	--help            to see this help
	--license         to see license
	--install         to install/update rbenv
	--backup          to create backup of plugins and versions folders in ~/.rbenv_bak
	--unistall        to uninstall rbenv completely
	--no-ruby-build   to install/update rbenv without ruby-build plugin (not recommended)
	--only-ruby-build to install/update only ruby-build plugin
	--uninstall-ruby-build
    	              to uninstall ruby-build plugin

Created to prove you could work on 4 lines of code from *Basic Github checkout* of [rbenv] which provides easy maintanance tool for Ruby language interpreters. This is first release, thus if you have found a bug, don't hesitate to create an issue.

License
----

MIT

Creator
----

[Szymon Błaszczyński]

[rbenv]:https://github.com/sstephenson/rbenv
[Szymon Błaszczyński]:mailto:szymon.smok@gmail.com?subject=rbenv-install
