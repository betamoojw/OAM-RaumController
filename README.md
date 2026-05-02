OAM-RaumController
===

Implementation of an knx application, which combines some [OpenKNX-Projects](https://github.com/OpenKNX) to provide an ETS programmable device. It allows a parametrization via ETS in general, this project requires ETS 5.7 or higher.

It is a PlatformIO project and needs a working ETS 5.7 (or higher) installed on the same PC.

It uses some Modules from the OpenKNX project to implement a device, which can automate a Room in a House.

For more information look into our [OpenKNX-wiki](https://github.com/OpenKNX/OpenKNX/wiki).

Thanks to all, who made this project successful.


===

RaumController (as a “room brain” running on a KNX device) is a complete KNX *room-level* control application that combines sensors, logic, and control functions into one device to manage everything inside a room.

RaumController (different from other simple KNX devices):
    sensor + logic engine + actuator coordination
    ➡️ all-in-one room automation node

RaumController = a decentralized KNX room automation controller
    combines inputs + logic + outputs
    runs fully on-device
    replaces the need for:
        separate logic controllers
        multiple single-purpose KNX devices