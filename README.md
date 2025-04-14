# MicroPython WIFI FTP
For easy to transfer files into MCUs running MicroPython.

# Usage
Just change ssid and password in ftp.py and copy ftp.py into like Raspberry Pi Pico w,
then run it, it will start a ftp server on your Micropython device.

output looks like this:

```
MPY: soft reboot
('192.168.4.42', '255.255.252.0', '192.168.4.1', '192.168.4.1')
FTP server started on 192.168.4.42:21
```

You can use FileZilla or other FTP client on your computer to connect to your MicroPython device and transfer files.