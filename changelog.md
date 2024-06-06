Changelog ( 06/06/2024 ) // RAIDER
====================================
* Rebased on Lineage-21 Kernel 4.14.336
* Rebrand to Raider
* Optimize GPU Boost
* Increase frequency of DVFS sampling even more
* Enable IO Boost & Disable Debug Latch
* Unlock all gpufreq
* Hardcode GPU Min/Max Freq

Changelog ( 7/10/2023 ) // V2-STABLE
====================================
* Fixed a bug where fast-charging doesnt work properly while screen on
* Fixed a bug where fast-charging speeds would often fluctuate when above 50%
* Improved UI Performance And Battery Backup
* Enable Sched WALT
* lancelot_defconfig : Build DTBO Projects for shiva too.
* Disable a bunch of logging from mediatek kernel drivers
* Enable ZRAM Dedup and ZRAM Writeback
* Set GRALLOC_EXTRA Config NUM to 10 
* Use the stock configs from MIUI_12.5.6.0  for proc/config.gz
* Increase frequency of DVFS sampling
* Affine GPU IRQs to big cluster
* enable CLEANCACHE
* Force strict fsync mod
* Improved Wifi Signals ( Enable 40Mhz Band and Fix Disconnection )
* [CAF-PORT] mm: checkout some files from LA.UM.9.1.r1-08100-SMxxx0.0 
* cpumask: Add cpumasks for big and LITTLE CPU clusters
* UPSTREAM: zram: support page writeback 
* tcp_output: set initial TCP window size to 64K (speed improvement) 
* cpuidle: don't disable cpuidle when entering suspend 
* lz4: fix kernel decompression speed
