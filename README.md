=== ВОССТАНОВЛЕНИЕ Wi-Fi BCM4364 ===

ДЛЯ MAC MINI С BROADCOM BCM4364

ШАГИ УСТАНОВКИ:
1. Скопируйте папку BCM4364_WiFi_Backup на Linux систему
2. Выполните: chmod +x install_script.sh
3. Выполните: ./install_script.sh
4. Перезагрузите: sudo reboot
5. Подключитесь к Wi-Fi: sudo nmcli --ask dev wifi connect "SSID"

ВАЖНЫЕ ФАЙЛЫ ПРОШИВКИ:
- brcmfmac4364b2-pcie.apple,ekans.bin
- brcmfmac4364b2-pcie.apple,ekans.clm_blob  
- brcmfmac4364b2-pcie.apple,ekans.txcap_blob
- brcmfmac4364b3-pcie.apple,bali.bin
- и другие файлы из apple-bcm-firmware

СОХРАНИТЕ ЭТУ ПАПКУ ДЛЯ БУДУЩИХ ПЕРЕУСТАНОВОК!
