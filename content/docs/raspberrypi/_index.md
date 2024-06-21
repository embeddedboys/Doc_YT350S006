+++
Title = "RaspberryPi"
weight = 10
+++

The log of booting process on Raspberry Pi 1B
```c
[    0.000000] Booting Linux on physical CPU 0x0
[    0.000000] Linux version 6.6.20+rpt-rpi-v6 (debian-kernel@lists.debian.org))
[    0.000000] CPU: ARMv6-compatible processor [410fb767] revision 7 (ARMv7), cd
[    0.000000] CPU: PIPT / VIPT nonaliasing data cache, VIPT nonaliasing instrue
[    0.000000] OF: fdt: Machine model: Raspberry Pi Model B Rev 2
[    0.000000] random: crng init done
[    0.000000] Memory policy: Data cache writeback
[    0.000000] Reserved memory: created CMA memory pool at 0x0b400000, size 256B
[    0.000000] OF: reserved mem: initialized node linux,cma, compatible id sharl
[    0.000000] OF: reserved mem: 0x0b400000..0x1b3fffff (262144 KiB) map reusaba
[    0.000000] Zone ranges:
[    0.000000]   Normal   [mem 0x0000000000000000-0x000000001bffffff]
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x0000000000000000-0x000000001bffffff]
[    0.000000] Initmem setup node 0 [mem 0x0000000000000000-0x000000001bffffff]
[    0.000000] Kernel command line: coherent_pool=1M snd_bcm2835.enable_headphot
[    0.000000] Dentry cache hash table entries: 65536 (order: 6, 262144 bytes, )
[    0.000000] Inode-cache hash table entries: 32768 (order: 5, 131072 bytes, l)
[    0.000000] Built 1 zonelists, mobility grouping on.  Total pages: 113680
[    0.000000] mem auto-init: stack:all(zero), heap alloc:off, heap free:off
[    0.000000] Memory: 165396K/458752K available (10000K kernel code, 1478K rwd)
[    0.000000] SLUB: HWalign=32, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
[    0.000000] ftrace: allocating 34944 entries in 103 pages
[    0.000000] ftrace: allocated 103 pages with 5 groups
[    0.000000] trace event string verifier disabled
[    0.000000] NR_IRQS: 16, nr_irqs: 16, preallocated irqs: 16
[    0.000006] sched_clock: 32 bits at 1000kHz, resolution 1000ns, wraps every s
[    0.000066] clocksource: timer: mask: 0xffffffff max_cycles: 0xffffffff, maxs
[    0.000167] bcm2835: system timer (irq = 27)
[    0.001006] Console: colour dummy device 80x30
[    0.001047] printk: console [tty1] enabled
[    0.001771] Calibrating delay loop... 697.95 BogoMIPS (lpj=3489792)
[    0.060318] CPU: Testing write buffer coherency: ok
[    0.060440] pid_max: default: 32768 minimum: 301
[    0.060620] LSM: initializing lsm=capability,integrity
[    0.060973] Mount-cache hash table entries: 1024 (order: 0, 4096 bytes, line)
[    0.061058] Mountpoint-cache hash table entries: 1024 (order: 0, 4096 bytes,)
[    0.062550] cgroup: Disabling memory control group subsystem
[    0.065102] RCU Tasks Rude: Setting shift to 0 and lim to 1 rcu_task_cb_adju.
[    0.065463] RCU Tasks Trace: Setting shift to 0 and lim to 1 rcu_task_cb_adj.
[    0.065829] Setting up static identity map for 0x8220 - 0x8258
[    0.067359] devtmpfs: initialized
[    0.080104] VFP support v0.3: implementor 41 architecture 1 part 20 variant 5
[    0.080649] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, ms
[    0.080754] futex hash table entries: 256 (order: -1, 3072 bytes, linear)
[    0.119943] pinctrl core: initialized pinctrl subsystem
[    0.121965] NET: Registered PF_NETLINK/PF_ROUTE protocol family
[    0.124563] DMA: preallocated 1024 KiB pool for atomic coherent allocations
[    0.132018] audit: initializing netlink subsys (disabled)
[    0.132575] audit: type=2000 audit(0.130:1): state=initialized audit_enabled1
[    0.133810] thermal_sys: Registered thermal governor 'step_wise'
[    0.134191] hw-breakpoint: found 6 breakpoint and 1 watchpoint registers.
[    0.134295] hw-breakpoint: maximum watchpoint size is 4 bytes.
[    0.134826] Serial: AMBA PL011 UART driver
[    0.144418] bcm2835-mbox 2000b880.mailbox: mailbox enabled
[    0.170878] raspberrypi-firmware soc:firmware: Attached to firmware from 202t
[    0.180912] raspberrypi-firmware soc:firmware: Firmware hash is f4e2138c2adca
[    0.196392] kprobes: kprobe jump-optimization is enabled. All kprobes are op.
[    0.205389] bcm2835-dma 20007000.dma-controller: DMA legacy API manager, dma1
[    0.208377] SCSI subsystem initialized
[    0.208926] usbcore: registered new interface driver usbfs
[    0.209071] usbcore: registered new interface driver hub
[    0.209218] usbcore: registered new device driver usb
[    0.210106] pps_core: LinuxPPS API ver. 1 registered
[    0.210179] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giom>
[    0.210280] PTP clock support registered
[    0.223619] clocksource: Switched to clocksource timer
[    0.224596] VFS: Disk quotas dquot_6.6.0
[    0.224759] VFS: Dquot-cache hash table entries: 1024 (order 0, 4096 bytes)
[    0.225042] FS-Cache: Loaded
[    0.226030] CacheFiles: Loaded
[    0.269497] NET: Registered PF_INET protocol family
[    0.269945] IP idents hash table entries: 8192 (order: 4, 65536 bytes, linea)
[    0.274601] tcp_listen_portaddr_hash hash table entries: 1024 (order: 0, 409)
[    0.274741] Table-perturb hash table entries: 65536 (order: 6, 262144 bytes,)
[    0.274812] TCP established hash table entries: 4096 (order: 2, 16384 bytes,)
[    0.274932] TCP bind hash table entries: 4096 (order: 3, 32768 bytes, linear)
[    0.275081] TCP: Hash tables configured (established 4096 bind 4096)
[    0.275266] UDP hash table entries: 256 (order: 0, 4096 bytes, linear)
[    0.275367] UDP-Lite hash table entries: 256 (order: 0, 4096 bytes, linear)
[    0.275783] NET: Registered PF_UNIX/PF_LOCAL protocol family
[    0.285242] RPC: Registered named UNIX socket transport module.
[    0.285338] RPC: Registered udp transport module.
[    0.285375] RPC: Registered tcp transport module.
[    0.285406] RPC: Registered tcp-with-tls transport module.
[    0.285438] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    0.286075] armv6-pmu arm-pmu: hw perfevents: no irqs for PMU, sampling evend
[    0.286206] hw perfevents: enabled with armv6_1176 PMU driver, 3 counters ave
[    0.291147] Trying to unpack rootfs image as initramfs...
[    4.524643] Initialise system trusted keyrings
[    4.540807] workingset: timestamp_bits=14 max_order=17 bucket_order=3
[    4.541035] zbud: loaded
[    4.542693] NFS: Registering the id_resolver key type
[    4.542824] Key type id_resolver registered
[    4.542868] Key type id_legacy registered
[    4.542982] nfs4filelayout_init: NFSv4 File Layout Driver Registering...
[    4.543039] nfs4flexfilelayout_init: NFSv4 Flexfile Layout Driver Registerin.
[    4.544620] Key type asymmetric registered
[    4.544717] Asymmetric key parser 'x509' registered
[    4.544947] Block layer SCSI generic (bsg) driver version 0.4 loaded (major )
[    4.545018] io scheduler mq-deadline registered
[    4.545059] io scheduler kyber registered
[    4.545230] io scheduler bfq registered
[    4.549250] simple-framebuffer 1eaa9000.framebuffer: framebuffer at 0x1eaa90s
[    4.549368] simple-framebuffer 1eaa9000.framebuffer: format=a8r8g8b8, mode=70
[    4.555696] Console: switching to colour frame buffer device 90x30
[    4.579082] simple-framebuffer 1eaa9000.framebuffer: fb0: simplefb registere!
[    4.605409] bcm2835-rng 20104000.rng: hwrng registered
[    4.609282] vc-mem: phys_addr:0x00000000 mem_base=0x1ec00000 mem_size:0x2000)
[    4.670245] brd: module loaded
[    4.703410] loop: module loaded
[    4.717890] Loading iSCSI transport class v2.0-870.
[    4.723569] usbcore: registered new interface driver smsc95xx
[    4.726967] dwc_otg: version 3.00a 10-AUG-2012 (platform bus)
[    5.247816] Freeing initrd memory: 10204K
[    5.469427] Core Release: 2.80a
[    5.472663] Setting default values for core params
[    5.475794] Finished setting default values for core params
[    5.679070] Using Buffer DMA mode
[    5.682243] Periodic Transfer Interrupt Enhancement - disabled
[    5.685388] Multiprocessor Interrupt Enhancement - disabled
[    5.688454] OTG VER PARAM: 0, OTG VER FLAG: 0
[    5.691554] Dedicated Tx FIFOs mode
[    5.695866]
[    5.695895] WARN::dwc_otg_hcd_init:1072: FIQ DMA bounce buffers: virt = cb504
[    5.705207] FIQ FSM acceleration enabled for :
[    5.705207] Non-periodic Split Transactions
[    5.705207] Periodic Split Transactions
[    5.705207] High-Speed Isochronous Endpoints
[    5.705207] Interrupt/Control Split Transaction hack enabled
[    5.719664]
[    5.719680] WARN::hcd_init_fiq:457: FIQ on core 0
[    5.725000]
[    5.725012] WARN::hcd_init_fiq:458: FIQ ASM at c073218c length 36
[    5.730294]
[    5.730310] WARN::hcd_init_fiq:496: MPHI regs_base at dc810000
[    5.735818] dwc_otg 20980000.usb: DWC OTG Controller
[    5.738669] dwc_otg 20980000.usb: new USB bus registered, assigned bus numbe1
[    5.741557] dwc_otg 20980000.usb: irq 56, io mem 0x00000000
[    5.744449] Init: Port Power? op_state=1
[    5.747247] Init: Power Port (0)
[    5.750434] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002, b6
[    5.756130] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber1
[    5.759117] usb usb1: Product: DWC OTG Controller
[    5.762026] usb usb1: Manufacturer: Linux 6.6.20+rpt-rpi-v6 dwc_otg_hcd
[    5.765064] usb usb1: SerialNumber: 20980000.usb
[    5.769426] hub 1-0:1.0: USB hub found
[    5.772562] hub 1-0:1.0: 1 port detected
[    5.777384] usbcore: registered new interface driver usb-storage
[    5.780877] mousedev: PS/2 mouse device common for all mice
[    5.787129] sdhci: Secure Digital Host Controller Interface driver
[    5.790208] sdhci: Copyright(c) Pierre Ossman
[    5.793528] sdhci-pltfm: SDHCI platform and OF driver helper
[    5.798487] ledtrig-cpu: registered to indicate activity on CPUs
[    5.802115] hid: raw HID events driver (C) Jiri Kosina
[    5.805496] usbcore: registered new interface driver usbhid
[    5.808583] usbhid: USB HID core driver
[    5.817809] Initializing XFRM netlink socket
[    5.821482] NET: Registered PF_PACKET protocol family
[    5.825166] Key type dns_resolver registered
[    5.868281] registered taskstats version 1
[    5.871509] Loading compiled-in X.509 certificates
[    5.903944] Indeed it is in host mode hprt0 = 00021501
[    5.967461] uart-pl011 20201000.serial: cts_event_workaround enabled
[    5.971464] 20201000.serial: ttyAMA0 at MMIO 0x20201000 (irq = 81, base_baud2
[    5.977604] printk: console [ttyAMA0] enabled
[    6.977674] bcm2835-wdt bcm2835-wdt: Broadcom BCM2835 watchdog timer
[    6.987934] bcm2835-power bcm2835-power: Broadcom BCM2835 power domains drivr
[    7.000864] sdhost: log_buf @ c25b2429 (8b503000)
[    7.057373] mmc0: sdhost-bcm2835 loaded - DMA enabled (>1)
[    7.069574] of_cfs_init
[    7.075595] of_cfs_init: OK
[    7.082918] clk: Disabling unused clocks
[    7.100540] Freeing unused kernel image (initmem) memory: 452K
[    7.109551] Kernel memory protection not selected by kernel config.
[    7.118921] usb 1-1: new high-speed USB device number 2 using dwc_otg
[    7.128788] Indeed it is in host mode hprt0 = 00001101
[    7.197287] Run /init as init process
[    7.259860] mmc0: host does not support reading read-only switch, assuming we
[    7.274494] mmc0: Host Software Queue enabled
[    7.282112] mmc0: new high speed SDHC card at address 0001

Raspbian GNU/Linux 12 raspberrypi ttyAMA0

raspberrypi login: pi
Password:
Linux raspberrypi 6.6.20+rpt-rpi-v6 #1 Raspbian 1:6.6.20-1+rpt1 (2024-03-07) armv6l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Mon Jun  3 04:56:36 BST 2024 on ttyAMA0
pi@raspberrypi:~$
```

__Hugo Clarity__ is a technology-minded theme for Hugo based on VMware's open-source [Clarity Design System](https://clarity.design/) featuring rich code support, dark/light mode, mobile support, and much more. See [a live demo at __neonmirrors.net__](https://neonmirrors.net/).

{{< button "./getting-started/" "Get started with Clarity" >}}
