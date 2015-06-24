# do-not-pollute-users-home-directory
My notes for the project "Don't pollute $HOME"

Dear open source software developers. Please don't create directories directly in $HOME.

Use a matching sub directory: http://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html

$XDG_DATA_HOME --> $HOME/.local/share
$XDG_CONFIG_HOME --> $HOME/.config
$XDG_CACHE_HOME --> $HOME/.cache

# My issues
https://bugs.launchpad.net/launchpadlib/+bug/1468476
