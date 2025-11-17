# ECB02C-BLE-AT-Commands
An uncomplete collection of AT-Commands understood by the ECB02C BLE Bluetooth module


# **Bluetooth serial port module BLE5.2 ECB02C BLE AT-Commands**
![TopView of ECB02C module](https://github.com/kywalda/ECB02C-BLE-AT-Commands/blob/main/BLE%205.2.%20Module%20ECB02C%20TopView_M.png)
|Default Port Config:|115200 bps, 8, 1, 1, None, None, (DTR)|
| :- | :- |
|||
|AT+RST|Reset|
|AT+FACTORY|Reset to factory defaults|
|AT|Answer: OK|
|AT+VER?|Get Version|
|AT+NAME?|Get device name|
|AT+NAME=*MYNAME*|Set device name|
|AT+ROLE?|Get Role (Central [Master] or Peripheral [Slave])|
|AT+ROLE=1|Set Role 1(Central) or 2([or <> 1] Peripheral)|
|AT+MAC?|Get device Mac Address|
|AT+SCAN|List available devices (works only if ROLE=1)|
|AT+BOND?|Get connected device|
|AT+LINK?|Get connection status|
|AT+BONDMAC=*EC230905EBA7*|Bind to available device using its Mac address|
|AT+BONDNAME=*YOURNAME*|Bind to available device using its Name|
|AT+SLEEP?|Get sleep mode: 0 (never sleep) or 1 (sleep if sleep_pin is low)|
|AT+SLEEP=*0*|Set sleep mode to 0 (never sleep) or 1 (sleep if sleep_pin is low)|
|AT+POWE?|Get TX Power|
|AT+POWE=*9*|Set TX Power from 0 to 9 3db steps|
|AT+MODE?|Get modus|
|AT+MODE=*0*|Set AT-Execution Mode to 0(executed when AT_en-Pin), 1(AT-commands were executed other bypassed), 2(anything bypassed)|
|AT+ECHO?|Get Echo status (0: no echo; 1: echo last command)|
|AT+ECHO=*1*|Set Echo (0: no echo; 1: echo last command)|
|AT+CONNOTIFY?|Get state of connection notifier 1 on or 0 off|
|AT+CONNOTIFY=*1*|Set connection notifier 1 on or 0 off|
|AT+CONPARAM=*0*|Set connection parameters (only in Slave Mode) 0:faster, more power; 1:slower, less power|
|AT+PASSWORD?|Get Connection Password|
|AT+PASSWORD=*1234*|Set Connection Password to 1234|
|AT+PASSWORDC|Forget the password|
