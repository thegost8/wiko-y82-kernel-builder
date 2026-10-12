  AR      drivers/virtio/built-in.o
  CC      drivers/video/fbdev/core/fbmon.o
  CC      drivers/usb/notify/usb_notify.o
  CC      drivers/usb/gadget/function/f_ss_mon_gadget.o
  CC      drivers/usb/gadget/function/f_conn_gadget.o
  CC      drivers/video/fbdev/core/fbcmap.o
  CC      drivers/usb/musb/musb_trace.o
  CC      drivers/usb/notify/usb_notify_sysfs.o
  CC      drivers/video/fbdev/core/fbsysfs.o
  AR      drivers/usb/gadget/function/usb_f_acm.o
  AR      drivers/usb/gadget/function/usb_f_serial.o
  AR      drivers/usb/gadget/function/usb_f_rndis.o
  AR      drivers/usb/gadget/function/usb_f_mass_storage.o
  AR      drivers/usb/gadget/function/usb_f_fs.o
  AR      drivers/usb/gadget/function/usb_f_midi.o
  AR      drivers/usb/gadget/function/usb_f_mtp.o
  AR      drivers/usb/gadget/function/usb_f_ptp.o
  AR      drivers/usb/gadget/function/usb_f_audio_source.o
  AR      drivers/usb/gadget/function/usb_f_accessory.o
  AR      drivers/usb/gadget/function/usb_f_vser.o
  AR      drivers/usb/gadget/function/usb_f_ss_mon_gadget.o
  AR      drivers/usb/gadget/function/usb_f_conn_gadget.o
  AR      drivers/usb/gadget/function/built-in.o
  AR      drivers/usb/gadget/libcomposite.o
  AR      drivers/usb/gadget/built-in.o
  CC      drivers/watchdog/watchdog_core.o
  CC      drivers/usb/musb/musb_virthub.o
  CC      drivers/usb/notify/dock_notify.o
  CC      drivers/watchdog/watchdog_dev.o
  CC      drivers/video/fbdev/core/modedb.o
  CC      drivers/usb/musb/musb_host.o
  CC      drivers/usb/notify/host_notify_class.o
  CC      drivers/watchdog/sprd_wdt_fiq.o
  CC      drivers/usb/notify/external_notify.o
  CC      drivers/video/fbdev/core/fbcvt.o
  CC      drivers/watchdog/sprd_pmic_wdt.o
  CC      drivers/video/fbdev/core/fb_defio.o
  CC      drivers/usb/notify/usb_notifier_sprd.o
  AR      drivers/watchdog/watchdog.o
  AR      drivers/watchdog/built-in.o
  CC      drivers/video/videomode.o
  CC      drivers/usb/musb/musb_gadget_ep0.o
  AR      drivers/usb/notify/usb_notify_layer.o
  AR      drivers/usb/notify/built-in.o
  CC      drivers/video/of_display_timing.o
  CC      drivers/usb/musb/musb_gadget.o
  CC      drivers/video/fbdev/core/cfbfillrect.o
  CC      drivers/video/of_videomode.o
  CC      drivers/usb/phy/phy.o
  CC      drivers/usb/serial/usb-serial.o
  CC      drivers/video/fbdev/core/cfbcopyarea.o
  CC      drivers/usb/musb/musb_debugfs.o
  CC      drivers/usb/phy/of.o
  CC      drivers/usb/musb/sprd_musbhsdma.o
  CC      drivers/video/fbdev/core/cfbimgblt.o
  CC      drivers/usb/phy/otg-wakelock.o
  CC      drivers/usb/serial/generic.o
  CC      drivers/usb/phy/class-dual-role.o
  CC      drivers/video/fbdev/core/sysfillrect.o
  CC      drivers/usb/musb/musb_sprd.o
  CC      drivers/usb/phy/phy-sprd-sharkl3.o
  CC      drivers/usb/serial/bus.o
  CC      drivers/video/fbdev/core/syscopyarea.o
  AR      drivers/usb/serial/usbserial.o
  AR      drivers/usb/serial/built-in.o
  CC      drivers/video/fbdev/core/sysimgblt.o
  AR      drivers/usb/phy/built-in.o
  CC      drivers/video/fbdev/core/fb_sys_fops.o
  CC      drivers/usb/storage/scsiglue.o
  AR      drivers/usb/musb/musb_hdrc.o
  AR      drivers/usb/musb/built-in.o
  AR      drivers/video/fbdev/core/fb.o
  CC      drivers/usb/storage/protocol.o
  AR      drivers/video/fbdev/core/built-in.o
  CC      drivers/usb/typec/class.o
  AR      drivers/video/fbdev/built-in.o
  AR      drivers/video/built-in.o
  CC      drivers/usb/typec/mux.o
  CC      drivers/usb/typec/bus.o
  CC      drivers/usb/storage/transport.o
  AR      drivers/usb/typec/altmodes/built-in.o
  CC      drivers/usb/storage/usb.o
  CC      drivers/usb/typec/ucsi/ucsi.o
  CC      drivers/usb/storage/initializers.o
  CC      drivers/usb/storage/sierra_ms.o
  CC      drivers/usb/storage/option_ms.o
  CC      drivers/usb/typec/ucsi/trace.o
  CC      drivers/usb/typec/sc27xx_typec.o
  CC      drivers/usb/storage/usual-tables.o
  AR      drivers/usb/typec/ucsi/typec_ucsi.o
  AR      drivers/usb/typec/ucsi/built-in.o
  AR      drivers/usb/typec/typec.o
  AR      drivers/usb/storage/usb-storage.o
  AR      drivers/usb/storage/built-in.o
  AR      drivers/usb/typec/built-in.o
  AR      drivers/usb/built-in.o
  AR      drivers/built-in.o
  GEN     .version
  CHK     include/generated/compile.h
  UPD     include/generated/compile.h
  CC      init/version.o
  AR      init/built-in.o
  AR      built-in.o
  LD      vmlinux.o
  MODPOST vmlinux.o
aarch64-linux-gnu-ld: drivers/gpu/drm/sprd/sprd_panel.o: in function `sprd_panel_esd_work_func':
/home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/gpu/drm/sprd/sprd_panel.c:804: undefined reference to `gcore_tp_esd_fail'
aarch64-linux-gnu-ld: drivers/gpu/drm/sprd/sprd_panel.o: relocation R_AARCH64_ADR_PREL_PG_HI21 against symbol `gcore_tp_esd_fail' which may bind externally can not be used when making a shared object; recompile with -fPIC
/home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/gpu/drm/sprd/sprd_panel.c:804:(.text+0xa5c): dangerous relocation: unsupported relocation
aarch64-linux-gnu-ld: /home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/gpu/drm/sprd/sprd_panel.c:804: undefined reference to `gcore_tp_esd_fail'
aarch64-linux-gnu-ld: drivers/gpu/drm/sprd/sprd_panel.o: in function `sprd_panel_prepare':
/home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/gpu/drm/sprd/sprd_panel.c:313: undefined reference to `nvt_resume_for_earlier'
aarch64-linux-gnu-ld: /home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/gpu/drm/sprd/sprd_panel.c:292: undefined reference to `himax_resume_by_ddi'
aarch64-linux-gnu-ld: drivers/mmc/core/slot-gpio.o: in function `mmc_gpio_cd_irqt':
/home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/mmc/core/slot-gpio.c:52: undefined reference to `call_sar_notifiers'
aarch64-linux-gnu-ld: /home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/mmc/core/slot-gpio.c:57: undefined reference to `sdcard_hx9031_notify'
aarch64-linux-gnu-ld: drivers/mmc/core/slot-gpio.o: relocation R_AARCH64_ADR_PREL_PG_HI21 against symbol `sdcard_hx9031_notify' which may bind externally can not be used when making a shared object; recompile with -fPIC
/home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/mmc/core/slot-gpio.c:57:(.text+0x1e8): dangerous relocation: unsupported relocation
aarch64-linux-gnu-ld: /home/runner/work/wiko-y82-kernel-builder/wiko-y82-kernel-builder/kernel/drivers/mmc/core/slot-gpio.c:57: undefined reference to `sdcard_hx9031_notify'
make: *** [Makefile:1184: vmlinux] Error 1
