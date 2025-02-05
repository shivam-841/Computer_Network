# Switch Commands Documentation

## 1. **show version**
### Description:
Displays information about the switch, including hardware details, software version, system uptime, and other system-related data.

### Example:
```
Switch> show version
```
### Sample Output:
```
Cisco IOS Software, C3560 Software (C3560-IPBASEK9-M), Version 15.2(4)E6
Technical Support: http://www.cisco.com/techsupport
...
System image file is "flash:c3560-ipbasek9-mz.152-4.E6.bin"
```

## 2. **? (conf?) or (configure ?)**
### Description:
The `?` command is used to display available commands in the current mode. If used with `configure ?`, it provides available configuration options.

### Example:
```
Switch# ?
```
### Sample Output:
```
Exec commands:
 enable    Turn on privileged commands
 disable   Turn off privileged commands
 configure Enter configuration mode
```

```
Switch# configure ?
 terminal    Enter configuration mode
```

## 3. **enable**
### Description:
Switches the user to privileged EXEC mode (also called enable mode), allowing access to advanced configuration and troubleshooting commands.

### Example:
```
Switch> enable
Switch#
```

## 4. **disable**
### Description:
Exits privileged EXEC mode and returns to user EXEC mode.

### Example:
```
Switch# disable
Switch>
```

## 5. **configure terminal**
### Description:
Used in privileged EXEC mode to enter global configuration mode, where the switch can be configured.

### Example:
```
Switch# configure terminal
Switch(config)#
```

## 6. **exit**
### Description:
Used to exit from the current mode.

### Example:
- Exiting from global configuration mode to privileged EXEC mode:
```
Switch(config)# exit
Switch#
```
- Exiting from privileged EXEC mode to user EXEC mode:
```
Switch# exit
Switch>
```

## 7. **hostname S1**
### Description:
Sets or changes the hostname of the switch. This command is executed in global configuration mode.

### Example:
```
Switch(config)# hostname S1
S1(config)#
```

## 8. **show mac address-table** (User Mode)
### Description:
Displays the MAC address table, which contains information about dynamically and statically learned MAC addresses.

### Example:
```
Switch> show mac address-table
```
### Sample Output:
```
Mac Address Table
-------------------------------------------
Vlan    Mac Address       Type        Ports
----    -----------       --------    -----
  1     000a.bbbb.cccc    DYNAMIC     Fa0/1
  2     000b.cccc.dddd    DYNAMIC     Fa0/2
```

