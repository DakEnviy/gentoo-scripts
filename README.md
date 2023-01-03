# gentoo-scripts

Some useful scripts for gentoo.

- **qtop** - helps to know about time estimation for installing packages
- **esync** - alias for synchronization with layman and emerge (`layman -S` and `emerge --sync`)
- **eclt** - shows how long the system will be updated
- **eupd** - update script for emerge
- **rcms** - systemd-like alias for rc-service
- **enewyear** - rebuild the world in the new year
- **qorph** - find files that were not installed by the package manager

Every script has `AUTO_SUDO` constant, which runs script as sudo automatically.
If you want to enable this, write `AUTO_SUDO=1` instead of `AUTO_SUDO=0`

## Install

### Using eselect repository - preferred method

```
# eselect repository enable underworld
# emerge --sync
# emerge -a gentoo-scripts
```

### Using layman

```
# layman -a underworld
# layman -s underworld
# emerge -a gentoo-scripts
```

### Manual

Just place these scripts to /usr/bin directory.

## Requirements

**qtop**

- app-portage/portage-utils

**esync**

- sys-apps/portage
- app-portage/layman (optional)
- app-portage/portpeek (optional)

**eclt**

- sys-apps/portage
- app-portage/portage-utils

**eupd**

- sys-apps/portage
- app-portage/layman (optional)
- app-portage/portpeek (optional)

**rcms**

- sys-apps/openrc

**enewyear**

- sys-apps/portage

**qorph**

- \>=dev-lang/python-3.9
- app-portage/gentoolkit

