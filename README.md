aquaponic_control
=================

## Jump to Section
* [How to install](#how-to-install)
* [Notes](#notes)
* [License](#license)
* [Donate Me ![](https://www.paypalobjects.com/de_DE/DE/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TZMF3HP322F5U)

## How to install
---
[[Back To Top]](#jump-to-section)

Clone git repository

    git clone https://github.com/scurth/aquaponic_control.git

Create a crontab entry

    crontab -e
    */5 * * * * {YOURPATH}/aquaponic_control/YOCTOPUCE_HEATER

Modify the following values according to your needs:

    pt100uri
    relayuri
    uppertemp
    lowertemp


## Notes
---
   YOCTOPUCE\_HEATER uses a YOCTOPUCE PT100 sensor and YOCTORELAY to switch an aquarium heater to the desired state, depending on the current temperature and time of the day.

## License
---
[[Back To Top]](#jump-to-section)

Copyright © 2013 Sascha Curth

This software is licensed under [MIT License](http://scurth.mit-license.org/). environment control
