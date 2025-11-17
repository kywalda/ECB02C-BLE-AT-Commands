# ECB02C-BLE-AT-Commands
An uncomplete collection of AT-Commands understood by the ECB02C BLE Bluetooth module


# **Bluetooth serial port module BLE5.2 ECB02C BLE AT-Commands**
![TopView of ECB02C module](https://github.com/kywalda/ECB02C-BLE-AT-Commands/blob/main/BLE%205.2.%20Module%20ECB02C%20TopView.png)
|Port Config:|115200 bps, 8, 1, 1, None, None, (DTR)|
| :- | :- |
|||
|AT+FACTORY|Reset to factory defaults|
|AT|Answer: OK|
|AT+VER?|Get Version|
|AT+NAME?|Get device name|
|AT+NAME=*MYNAME*|Set device name|
|AT+ROLE?|Get Role (Central [Master] or Periphery [Slave])|
|AT+ROLE=1|Set Role 1(Central) or 2([or <> 1] Periphery)|
|AT+MAC?|Get device Mac Address|
|AT+SCAN?|List available devices|
|AT+BOND?|Get connected device|
|AT+BONDMAC=*EC230905EBA7*|Bind to available device using its Mac address|
|AT+BONDNAME=*YOURNAME*|Bind to available device using its Name|
|||
|||
