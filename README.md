
- cd sources kernel
- ` cd drivers/staging/prima/CORE/HDD/src/wlan_hdd_main.c `
- ` nano wlan_hdd_main.c `
- disable the netdevice notifier functions of the prima wlan driver) An alternative more appropriate fix is to add NULL or validity checks within the netdevice notifier functions.
- see example here ` https://github.com/jcadduono/nethunter_kernel_mako/commit/bda7cf4b08a04152a868e87b2f90070db6b88134 `
