# isd — *i*nteractive *s*ystem*d*

<!-- --8<-- [start:tagline] -->
> `isd` — a better way to work with `systemd` units

Simplify `systemd` management with `isd`!
`isd` is a TUI offering fuzzy search for units, auto-refreshing previews,
smart `sudo` handling, and a fully customizeable interface
for power-users and newcomers alike.
<!-- --8<-- [end:tagline] -->

<!-- --8<-- [start:features] -->
`isd` is a keyboard-focused, highly customizeable TUI with the following features:

- Quickly switch between `system` and `user` units
- Fuzzy search units
- Auto refresh previews
- Quickly open outputs in a pager or editor
- Auto `sudo` prefixing if required
- Auto rescale depending on terminal window size (fluid design)
- Extensive command palette with many keyboard shortcuts
- Fully configurable keybindings
- Optional input state caching for common inputs
- Theme support
- YAML configuration file _with auto-complete_
<!-- --8<-- [end:features] -->

## Demo

https://github.com/user-attachments/assets/4aad0902-6094-4fc2-90b9-b62456df22f5

[Click here for a higher quality recording](https://isd-project.github.io/isd/#working-with-isd).

## Documentation

The documentation is live at:

- <https://isd-project.github.io/isd>

## Road map

<!-- --8<-- [start:roadmap] -->
A collection of some _unordered_ ideas that could improve `isd`:

- [ ] Option to view the security rating of units
- [ ] Improve highlighting of `systemd` units (tree-sitter grammar)
- [ ] Write a custom, more secure `$EDITOR` integration (more secure `sytemctl edit`)
- [ ] Add icon for project and application menu
- [ ] Allow customization of preview windows
- [ ] Improve `journal_pager` integration
- [ ] Add custom sort options
- [ ] Faster fuzzy search
- [ ] Improve default themes
<!-- --8<-- [end:roadmap] -->


## Acknowledgments

<!-- --8<-- [start:acknowledgments] -->
Big thanks to the developers of:

- [systemd](https://systemd.io/) for creating the most widely used service manager for Linux
- [NixOS](https://nixos.org/) for peeking my interest in `systemd` and service managers
- [`sysz`](https://github.com/joehillen/sysz) for providing a starting point and a desire to build a more complex `systemctl` TUI
- [textual](https://textual.textualize.io/) for making it a breeze to create TUI's in Python
- [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) for building a solid and simple to use static site generator for the documentation
- [asciinema](https://docs.asciinema.org/) for developing an easy to use _and self-hosteable_ terminal recorder and player
- [vhs](https://github.com/charmbracelet/vhs) for creating a scriptable terminal program
<!-- --8<-- [end:acknowledgments] -->

