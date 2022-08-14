#!/bin/bash
sudo sed -i 's/subvol=@/subvol=@,ssd,noatime,space_cache,compress=zstd,discard=async/g' /usr/lib/partman/mount.d/70btrfs
sudo sed -i 's/subvol=@home/subvol=@home,ssd,noatime,space_cache,compress=zstd,discard=async/g' /usr/lib/partman/mount.d/70btrfs
sudo sed -i 's/pass=1/pass=0/g' /usr/lib/partman/fstab.d/btrfs
sudo sed -i 's/pass=2/pass=0/g' /usr/lib/partman/fstab.d/btrfs
sudo sed -i 's/subvol=@/subvol=@,ssd,noatime,space_cache,compress=zstd,discard=async/g' /usr/lib/partman/fstab.d/btrfs
sudo sed -i 's/subvol=@home/subvol=@home,ssd,noatime,space_cache,compress=zstd,discard=async/g' /usr/lib/partman/fstab.d/btrfs
