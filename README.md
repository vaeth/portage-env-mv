# portage-env-mv

These are Martin Väth's local `/etc/portage/env` and
`/etc/portage/package.cflags` directories (for gentoo),
full of local fixes and hacks.

This is mainly meant for personal use, but it is under the GPL v2 license.

The package.cflags subdirectory is meant to be used through portage-bashrc-mv
- https://github.com/vaeth/portage-bashrc-mv/

An ebuild for the latter is in the mv overlay (available over layman).

You can include local files into `*/local` (this is not under git control).

The login picture for slim should be provided this way in
- `/etc/portage/env/local/pic/login.jpg`

(`*/pic` or `*/login.jpg` can be a symlink which is resolved).


Moreover, some patches should be provided this way in one of

- `/etc/portage/env/local/patches`
- `/etc/portage/env/patches/local`
- `$MV_PATCHES`

