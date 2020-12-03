# Minimal MicroPython Captive Portal

This code is tested on ESP32. It creates a wifi access point, and once connected to it a captive portal is opened (served from `index.html`).

* Works with uasyncio v3 (MicroPython 1.13+)
* Fallback for earlier versions of uasyncio/MicroPython
* Code: [main.py](https://github.com/metachris/micropython-captiveportal/blob/master/main.py)

---

Notes

* License: MIT
* Author: Chris Hager <chris@linuxuser.at> / https://twitter.com/metachris
* Repository: https://github.com/metachris/micropython-captiveportal

Built upon

- https://github.com/p-doyle/Micropython-DNSServer-Captive-Portal

References

- http://docs.micropython.org/en/latest/library/uasyncio.html
- https://github.com/peterhinch/micropython-async/blob/master/v3/README.md
- https://github.com/peterhinch/micropython-async/blob/master/v3/docs/TUTORIAL.md
- https://www.w3.org/Protocols/rfc2616/rfc2616-sec5.html#sec5
