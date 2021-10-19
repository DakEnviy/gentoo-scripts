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
- app-portage/layman

**eclt**

- sys-apps/portage
- app-portage/portage-utils

**eupd**

- sys-apps/portage
- app-portage/layman

**rcms**

- sys-apps/openrc
