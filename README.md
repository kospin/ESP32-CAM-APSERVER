# ESP32-CAM-APSERVER

AP client 連線成功後開啟SoftAP server ssid : [Wifi.localIP()_apssid]
如設定apssid = 12308
取得的Wifi.localIP() = 192.168.43.31
則SoftAP server ssid = "192.168.43.31_12308"

如此只要知道apssid 再做wifi掃瞄 就可得到APserver ssid 和 Wifi.localIP()

[arduino-esp32 driver](https://github.com/espressif/arduino-esp32/releases)
