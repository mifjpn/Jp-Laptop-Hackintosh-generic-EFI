# Jp-Laptop-Hackintosh-generic-EFI
## Contents(EFIs)
1.Toshiba Dynabook CL4-T564-78L

2.NEC VersaPro PC-VK25TX

3.NEC VersaPro PC-VK24LF

4.NEC VersaPro PC-VK27MX

##overview
These EFIs have at least the Device settings required for the above laptops.
In other words, these are the EFIs that were able to boot into the installer.

##Points to remember
The USB connections have been confirmed, but they are not perfect.
WiFi and Bluetooth are unconfirmed. Please use a Lan cable.
The SMBIOS corresponding to the CPU is installed, but if you install an OS that exceeds it, please rewrite the SMBIOS.
You may need CryptexFixup.kext to interpolate instructions without a CPU command-set.

# Jp-Laptop-Hackintosh-generic-EFI
## 内容(EFI)
1.東芝 ダイナブック CL4-T564-78L

2.NEC VersaPro PC-VK25TX

3.NEC VersaPro PC-VK24LF

4.NEC VersaPro PC-VK27MX

##概要
これらの EFI には、少なくとも上記のラップトップに必要なデバイス設定がしてあります。
つまり、これらはインストーラーを起動できた EFI です。

##留意点
USB 接続は確認済みですが、完全ではありません。
WiFi、Bluetoothは未確認です。 LANケーブルをご利用ください。
CPUに対応したSMBIOSが搭載されていますが、それを超えるOSを搭載する場合はSMBIOSを書き換えてください。
CPUにない命令（AVX2)を補間するには、CryptexFixup.kext が必要になる場合があります。
