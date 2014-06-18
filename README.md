## nginx-overlay

This repository contains additional versions of gentoo's nginx ebuilds.

The main purpose is to keep older versions around for those that prefer to use
releases from the nginx 'stable' branch, although [upstream recommendation][1]
is to stick with mainline.

The repository will additionally contain newer and/or experimental versions
that requires additional testing before landing in the gentoo portage tree.

Older ebuilds will use unstable (~) keywording while experimental ebuilds
lacks any keywording. Please adjust your portage configuration
accordingly.

### Workflow

The **master** branch is always considered being production ready, which means
that all development should be made in branches. All commits and merges to
**master** should be signed off (`-s`) and preferably signed (`-S`). Always keep
history when merging a branch (`--no-ff`).

### Contributing

Contributions are welcome. Fork (preferably to a branch) and create a
pull request. Bugs to versions in the main gentoo tree should always be filed
in the [Gentoo Bugzilla][2].


[1]: http://nginx.com/blog/nginx-1-6-1-7-released/
[2]: http://bugs.gentoo.org
