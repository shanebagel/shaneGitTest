# This script creates logical volumes
# It first uses the parted utility to make labels for each disk, generates a partition, and enables LVM
# Next it created physical volumes out of the partitions and adds the PVs to a Volume Group,
# which then is used to create various Logical Volumes from the VG
# The device names, and sizes can be tweaked, as well as the names of the Volume Groups and Logical Groups, in this instance I had two block storage devices
# /dev/vdg and /dev/vdh 
