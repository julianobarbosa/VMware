# vim-cmd

## List all VMs registered to this host (This reveals the Vmid needed for other commands)
vim-cmd /vmsvc/getallvms

## Unregister a VM
vim-cmd /vmsvc/unregister "Vmid"

## Register a VM
vim-cmd /solo/register /path/to/file.vmx

## Get power state of a VM
vim-cmd /vmsvc/power.getstate "Vimid"

## Power off a VM
vim-cmd /vmsvc/power.off "Vmid"

## Power on a VM
vim-cmd /vmsvc/power.on "Vmid"
