# OpenSUSE-tweak-configs

disable synaptic touchpad driver and use libinput instead.

zypper rm xf86-input-synaptics
zypper al xf86-input-synaptics

sudo configuration
https://en.opensuse.org/SDB:Administer_with_sudo

memory leak fix
balooctl disable
