# MicroPython WIFI FTP
For easy to transfer files into MCUs running MicroPython.

# Usage
Just copy ftp.py through Thonny into like Raspberry Pi Pico w flash drive, then run it,
type input ssid & password, it will start a ftp server on your MicroPython device.

output looks like this:

```
MPY: soft reboot
ssid: xxxxxxx
password: xxxxxxx
('192.168.4.42', '255.255.252.0', '192.168.4.1', '192.168.4.1')
FTP server started on 192.168.4.42:21
```

You can use FileZilla or other FTP client on your computer to connect to your MicroPython device and transfer files.