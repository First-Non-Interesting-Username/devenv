Readme created according to instructions in [official stardance resources](https://stardance.hackclub.com/resources/how_to_ship#node=oss)

# Devenv contribution README for Stardance.

I contributed to [cachix/devenv](https://github.com/cachix/devenv), which is a nix based solution for developer environments.

I fixed the bug where the devcontainer configuration (which is crucial for codespaces for example) was a symlink to the nix store.

I submited 2 PRs: 

- [#2932](https://github.com/cachix/devenv/pull/2932) - frankly overenginnered, but it worked. Closed
- [#2951](https://github.com/cachix/devenv/pull/2951) - a far easier solution, implemented thanks to copy mode introducted because of my first PR. Merged

