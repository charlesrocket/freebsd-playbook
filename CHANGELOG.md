# Changelog

All notable changes to this project will be documented in this file.

## [1.10.1] - 2024-12-13

### Bug Fixes

- Drop Atheros driver

### Miscellaneous tasks

- Add nerd-fonts
- Add eww (bt) scripts
- Add xwayland
- Switch to libsecret
- Add keyring packages
- Add git-credential-oauth

### Operations

- Fix vagrant installation

## [1.10.0] - 2024-11-27

### Bug Fixes

- Update Kvantum package
- Rename emacs pkg task

### Features

- Add thinkpad settings
- Add emacs wayland support

### Miscellaneous tasks

- Add `devmode`
- Add `valgrind`
- Drop asus settings
- Drop libsecret helper

### Testing

- Disable clamav

## [1.9.2] - 2024-07-23

### Bug Fixes

- Update yubikey manager
- Update fido2
- Update qmk

### Miscellaneous tasks

- Add swayimg
- Upgrade dorst config
- Add `zola`
- Add `ruby`
- Add funding info
- Bump ansible to 2.17
- Drop `cxxmatrix`

### Operations

- Update actions
- Update labeler to v5
- Reformat labeler config
- Bump macos
- Configure dependabot
- Bump actions/setup-python from 3 to 5
- Install vagrant
- Install virtualbox
- Switch to ubuntu-latest
- Fix profile label
- Bump actions/deploy-pages from 1 to 4
- Bump actions/upload-pages-artifact from 1 to 3

### Styling

- Fix `ci` formatting

### Testing

- Fix network interfaces

## [1.9.1] - 2024-02-05

### Bug Fixes

- Add drm-kmod

### Miscellaneous tasks

- Enable wireguard
- Use new alacritty config

## [1.9.0] - 2024-01-05

### Bug Fixes

- Change `wg` defaults

### Miscellaneous tasks

- Bump ansible version
- Update LICENSE

### Operations

- Update linter
- Bump fbsd version

### Refactor

- Rename variables within roles

## [1.8.0] - 2023-12-05

### Bug Fixes

- Drop `sendmail` tasks
- Reimport `fetch_vars`

### Features

- Use `fetch_vars`

### Miscellaneous tasks

- Update dependencies
- Drop doas config
- Cleanup

## [1.7.1] - 2023-11-08

### Bug Fixes

- Tag profile tasks

## [1.7.0] - 2023-11-07

### Features

- Add `tethering` role
- Add tags

## [1.6.3] - 2023-10-30

### Bug Fixes

- Add missing `ohmyzsh` option
- Move `essential.git`

## [1.6.2] - 2023-10-28

### Bug Fixes

- Drop `ip_check_interface`

## [1.6.1] - 2023-10-26

### Bug Fixes

- Drop ykpers

### Documentation

- Update requirements

### Miscellaneous tasks

- Caja -> thunar

### Refactor

- Move ykpers

## [1.6.0] - 2023-10-24

### Documentation

- Update usage

### Features

- Add clamav role
- Add mfa role

### Miscellaneous tasks

- Add aria2
- Enable wifi
- Add aria2 config
- Add gpg config
- Remove redundant clamav package

### Revert

- Remove gpg config

## [1.5.0] - 2023-10-08

### Bug Fixes

- Drop redundant shell change

### Documentation

- Fix galaxy badge
- Update descriptions

### Features

- Add shell setting

### Operations

- Update `checkout`

## [1.4.1] - 2023-09-12

### Bug Fixes

- Update microcode task

### Documentation

- Comment pkg list

### Miscellaneous tasks

- Drop devcpu-data
- Update dependencies

### Testing

- Update profiles

## [1.4.0] - 2023-08-24

### Bug Fixes

- Update `pre_tasks`
- Fix repository catalogue

### Features

- Update branch option
- Change default branch

### Miscellaneous tasks

- Add perl5 package
- Update dependencies
- Drop lowbatt.sh
- Add get-volume
- Add dorst config
- Update pkg options

## [1.3.0] - 2023-05-01

### Bug Fixes

- Use `ansible_user` variable

### Documentation

- Edit arg spec descriptions

### Features

- Add more system options
- Show var states
- Improve `sys` (#14)
- SSH is enabled by default
- Add more server options
- Improve `mainframe` (#15)
- Add more desktop options
- Improve `desktop` (#16)

### Miscellaneous tasks

- Use `molecule-plugins`
- Update profiles
- Add `acpi`
- Update dotfiles list
- Add socat package
- Add battery script
- Add network script

### Testing

- Rename test tasks
- Increase verbosity
- Decrease verbosity

## [1.2.0] - 2023-04-20

### Bug Fixes

- Fix `bastille` argument specs
- Check dotfiles list
- Edit `poudriere_zfs`

### Documentation

- Update README.md

### Features

- Add `profile_version`
- Add defaults to `sys`
- Add/improve `kern_sec`
- Add defaults to `bastille`
- Add defaults to `poudriere`
- Add `ipv6_support` option

### Miscellaneous tasks

- Add pr template
- Update dependencies
- Don't deploy lynis profile if the binary is not installed
- Check if ohmyzsh needs deployment
- Enable IPv6
- Edit documentation link

### Operations

- Add pr labeler

### Testing

- Update molecule tests

## [1.1.0] - 2023-04-16

### Bug Fixes

- Add `user_groups` to argument specs
- Update desktop user groups
- Fix default options in argument specs

### Documentation

- Update argument specs
- Fix `wireguard` description
- Use external screenshot location
- Update `sshd` description

### Features

- Add default variables
- Add `wg` role
- Improve `accounting`
- Improve `sys`
- Add defaults to `qmk`
- Add defaults to `pkg_branch`
- Add default `upgrade_packages`
- Add defaults to `pf`

### Miscellaneous tasks

- Version bump
- Update profiles
- Bump `essential`
- Update galaxy tags
- Fix galaxy tags
- Update pkg lists
- Enable git-cliff package

### Refactor

- Drop `packages`

### Testing

- Update server variables

## [1.0.2] - 2023-04-11

### Documentation

- Update short descriptions
- Update `mainframe` descriptions

### Miscellaneous tasks

- Version bump
- Prepare for 1.0.2

### Performance

- Use `remote_vars` plugin

## [1.0.1] - 2023-04-07

### Bug Fixes

- Drop old SSH option
- Edit user groups task
- Ensure MOTD dependencies are installed
- Add default security level
- Download profiles from source
- Use explicit variable declaration
- Fix argument validation

### Documentation

- Fix docsite files
- Update header
- Update instructions
- Update branch
- Add extra links
- Add argument_specs.yml for `amd`
- Add extra documentation
- Fix docsite references
- Fix README.md
- Fix example variables
- Edit descriptions
- Add documentation for user profiles
- Update short descriptions
- Move `profiles`

### Miscellaneous tasks

- Version bump
- Change security level
- Fix formatting
- Prepare for 1.0.1

### Operations

- Drop docs.yml
- Add ansible-lint

### Styling

- Edit usage
- Update descriptions

### Testing

- Fix molecule
- Add test profiles
- Use test profiles
- Add `make_config` to desktop tests

### Build

- Update filter

### Revert

- Don't use explicit variable declaration

## [1.0.0] - 2023-04-03

### Bug Fixes

- Check `doom sync` output
- Check `pkg update` output
- Properly check hostname variable
- Move `make.conf` template
- Fix `motd.sh` permissions
- Use explicit octal
- Edit variables ext
- Source pkg config from remote
- Fix src parameters
- Fix ohmyzsh installer

### Documentation

- Update header
- Configure docsite
- Add missing role files
- Fix `desktop`, `pkg_branch`
- Add argument_specs
- Fix `virtualbox`
- Fix `wifi`
- Update README.md
- Edit `install`

### Features

- Add galaxy.yml
- Convert to `collection`
- Add kern_sec
- Use profile directory
- Set hostname
- Add `laptop`
- Add `desktop`
- Move powerd tasks
- Update timezone task
- Add `desktop`, `laptop`
- Update configuration
- Move C-states tasks
- Move desktop tasks
- Add `mainframe`
- Add `poudriere`
- Add `accounting`
- Move assets
- Improve roles
- Add `server`
- Add `doas_config`
- Add `microcode_update`
- Improve user task
- Set make config conditions
- Edit `server` conditionals
- Improve `pkg_branch`
- `pkg_branch` -> `pkg_latest_branch`

### Miscellaneous tasks

- Add CHANGELOG.md
- Fix galaxy.yml
- Update bootstrap script
- Fix permissions
- Drop old test files
- Drop verbosity setting
- Update `server` profile
- Update gitignore
- Drop `pkg_branch` register
- Add shell scripts to EditorConfig
- Bump `essential`
- Update `build_ignore`
- Move screenshot

### Operations

- Fix test script
- Add docsite workflow
- Use profiles
- Update scripts
- Switch to molecule
- Rename docsite workflow
- Fix `lint`
- Update linter

### Styling

- Fix formatting
- Fix `station`
- Fix YAML syntax
- Fix CD

### Testing

- Update test script
- Add build command
- Don't use latest branch
- Fix molecule
- Drop inventory links
- Include profile variables
- Fix vars filename
- Change verbosity
- Update server test
- Fix `package_facts`
- Add default test variables

### Conky

- Fix colors

### Waybar

- Force copy


