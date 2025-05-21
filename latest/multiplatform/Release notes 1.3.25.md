# Spoony 1.5.1 Release notes
## Firmware version 1.3.25
### Bugs correction

None

### New functionnalities

* **SoftUnit filter type "DIF" added**

In addition to existing *MIN* (minimum), *MAX* (maximum) and *AVG* (average) filter type, new type *DIF* has been added. This filter allows to compute Software DataPoints that are the difference between two consecutive values at configured update frequency. Typical application is to compute total Energy consumption over a defined period of time.

***
## Firmware version 1.3.24
### Bugs correction
* **WiFi DHCP Server memory leak corrected**

DHCP Server of WiFi Access Point interface was incorrectly receiving DHCP Discover/DHCP Request frames coming through Ethernet interface. In addition, DHCP Request frames with DHCP option 54 set were not deallocated properly, resulting in memory starving at Ethernet interface level after variable amount of time. This affected Spoony devices by rendering ethernet interface inoperative after some time. Both issues have been corrected.

* **Fixed memory leak on Http Server**

HttpMessageContent was not deallocating encoder. This resulted in a memory leak when using MVC APIs (Browse, Monitor etc.)

* **Fixed WebSocket Console**

Disconnecting from Console over Http interface was causing random resets. Websocket background worker and Console background worker have been properly synchronized to avoid situation where Websocket is deleted before Console worker exists properly. Stream deallocation is managed at Console worker task level.

### New functionnalities

None