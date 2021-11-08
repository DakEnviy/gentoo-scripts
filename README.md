# gentoo-scripts

Some useful scripts for gentoo.

- **qtop** - helps to know about time estimation for installing packages
- **esync** - alias for synchronization with layman and emerge (`layman -S` and `emerge --sync`)
- **eclt** - shows how long the system will be updated
- **eupd** - alias for synchronization and updating packages
- **rcms** - systemd-like alias for rc-service

## Requirements

**qtop**

- app-portage/portage-utils

**esync**

- sys-apps/portage

**eclt**

- sys-apps/portage
- app-portage/portage-utils

**eupd**

- sys-apps/portage

**rcms**

- sys-apps/openrc

## Install

### Using layman

```
# layman -o https://raw.githubusercontent.com/DakEnviy/underworld-overlay/master/repositories.xml -f -a underworld
# layman -s underworld
# emerge -a gentoo-scripts
```

### Manual

Just place these scripts to /usr/bin directory.

