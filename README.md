## <center> Hackintosh the Thinkpad X1 Carbon 6th Generation 

# notice

### DP

**audio:**
- PciRoot(0x0)/Pci(0x1F,0x3) 
    
| model | key           | Data Type | value    |
|:------|---------------|-----------|:---------|
| x1c4  | alc-layout-id | Data      | 0E000000 |
| x1c6  | alc-layout-id | Data      | 0B000000 | 

**video:**
- PciRoot(0x0)/Pci(0x2,0x0)  

| model | key           | Data Type | value    |
|:------|---------------|-----------|:---------|
| x1c4  | AAPL,ig-platform-id | Data      | 00001619 |
|  - | device-id | Data      | 16190000 |
| x1c6  | AAPL,ig-platform-id | Data      | 00001659  | 
| -  | device-id | Data      | 16590000  | 

### Kernel:
**usb:**
```
  USBToolBox.kext
  UTBMap.kext
``` 
**Wifi and Bluetooth:**
  ```
  AirportItlwm_for_Ventura.kext 
  BlueToolFixup.kext 
  IntelBluetoothFirmware.kext
  ```    
**Keyboard Input**
  ```
   VoodooPS2Controller.kext 
   VoodooPS2Controller.kext/Contents/PlugIns/VoodooPS2Keyboard.kext 
   VoodooPS2Controller.kext/Contents/PlugIns/VoodooPS2Mouse.kext
   VoodooPS2Controller.kext/Contents/PlugIns/VoodooPS2Trackpad.kext
   VoodooRMI.kext
   VoodooRMI.kext/Contents/PlugIns/VoodooInput.kext    
   VoodooSMBus.kext 
   VoodooRMI.kext/Contents/PlugIns/RMISMBus.kext 
  ```   
### notes：
- Only key data is listed here, other items have been omitted！
- updete for 2024.3.31 
  
### Reference link :

- x1c6-hackintosh repositories:
  - [benbender/x1c6-hackintosh](https://github.com/benbender/x1c6-hackintosh)
  - [zhtengw/EFI-for-X1C6-hackintosh](https://github.com/zhtengw/EFI-for-X1C6-hackintosh)   
- hackintosh resources
   - [sqlsec-hackintosh](https://github.com/sqlsec/Hackintosh)
   - [daliansky-hackintosh](https://blog.daliansky.net/)
