# 📱

### 🔌 Drivers USB

- [Motorola USB Drivers](https://es-ar.support.motorola.com/app/usb-drivers/)
- [Samsung USB Drivers](https://developer.samsung.com/android-usb-driver)

### 🖥️ ADB & Platform Tools

- [ADB + Fastboot](https://developer.android.com/studio/releases/platform-tools)
- [Platform Tools](https://developer.android.com/tools/releases/platform-tools)

---

## 📱 Desbloqueo de Dispositivos

### 📌 Samsung

- **Verificar Knox** (Al desbloquear bootloader se incrementa → pierde garantía)
- Desbloqueo limitado, root posible pero sin revertir Knox.

### 📌 Motorola

1. **OEM Unlock** → Activar en opciones de desarrollador.
2. **Desbloqueo de Bootloader** → Via comando `fastboot oem unlock` o página oficial.

---

## 🚀 Root

- [Magisk (Root)](https://github.com/topjohnwu/Magisk)

**Pasos:**
1. Parchear boot.img con Magisk.
2. Flashear el boot.img parchado via Fastboot.

---

## 🧩 LSPosed (Xposed para Android moderno)

- [LSPosed](https://github.com/LSPosed/LSPosed)
- [LSPosed Mod (Android 15+)](https://github.com/mywalkb/LSPosed_mod/releases)

**Instalación vía Magisk como módulo.**

---

## 🛡️ Privacidad

- [Hide My Applist](https://github.com/Dr-TSNG/Hide-My-Applist)

**Oculta apps para evitar detección por sistemas de seguridad o apps anti-root.**


https://github.com/Halhadus/selinux_permissive_hide/releases
