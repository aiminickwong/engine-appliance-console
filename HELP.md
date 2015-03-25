#### This is the management tool for oVirt Engine, you can use it to management the Engine system more convenient and faster.
=============
#####Usage:
* Note: You must initialize the configuration at first login, configuration method : 1-->2-->3-->7(3)-->7(6), when you complate the configuration, you can browse "http://{Web Portal IP}/ovirt-engine/services/health" to verify the engine status, if the respon is "DB Up!Welcome to Health Status!", the configuration is successfully. 
* When you login the console, you can get the summary infomation of the Engine Appliance:
```
    Welcome to the oVirt Engine Appliance.
    
    To manage your appliance please browse to Web Portal.
    
    	Hostname:		    aa.bb.cc
    	IP Address:		    192.168.2.195
    	Netmask:		    255.255.252.0
    	Gateway:		    192.168.0.1
    	DNS:                8.8.8.8
    	MAC Address:	    00:1A:4A:81:E3:67
    	System Time:        Fri Oct 17 13:30:33 CST 2014
    	
    	Engine Version:		3.5.0.1
    	Engine State:		Running
    	Web Portal:		    http://192.168.2.195
    
    
    Press any key to continue.
```

* Press any key to continue

```
    Advanced Setting
    
    1) Network Configuration
    2) Test Network Configuration
    3) Set Hostname
    4) Set Date and Time
    5) Hosts File Configuration
    6) Engine Restart
    7) Engine Advance Setting
    8) System Restart or Shutdown
    9) Shell
    10) Summary Information
    11) Help
    12) Log OFF
    
    
    Choose the advanced setting: 
```

* Press "1", [enter], configuration IP/Netmask/Gateway/DNS

```
    Network Configuration
    
    	IP Address:	192.168.3.250
    	Netmask:	255.255.252.0
    	Gateway:	192.168.0.1
    	DNS:		8.8.8.8
    
    Enter the new network configuration.
    
    Enter the IP Address or c to cancle: |192.168.3.250| 
    Enter the Netmask or c to cancle: |255.255.252.0| 
    Enter the Gateway or c to cancle: |192.168.0.1| 
    Enter the DNS or c to cancle: |8.8.8.8| 

```

* Press "2", [enter], test the network communication([enter]go back)

```
    Test Network Configuration
    
    Enter the hostname, ip address, or none to continue: 192.168.0.1
    192.168.0.1: Success!
    Enter the hostname, ip address, or none to continue:
```

* Press "3", [enter], modify the hostname

```
    Please enter the hostname: aa.bb.cc
```

* Press "4", [enter], modify the date of the system

```
    Date and Time Configuration
    
    Enter the current date (YYYY-MM-DD) or "c" to Cancel : 2014-10-17
    Enter the current time in 24 hour format (HH:MM:SS) or "c" to Cancel : 13:40:00

    Date and Time Configuration
    
    	Date :		2014-10-17
    	Time :		13:40:00
    
    Apply Date and Time configuration? (Y/N): Y
```

* Press "5",[enter], modify the "/etc/hosts" file

```
    127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4
    ::1         localhost localhost.localdomain localhost6 localhost6.localdomain6
    
    192.168.2.195 aa.bb.cc
```

* Press "6", [enter], restart "ovirt-engine" service

```
    Engine Restart (Y/N): Y
```

* Press "7", [enter], Advance configuration for Engine
 * Press "1", [enter], clean the configuration of Engine
 * Press "2", [enter], configuration the Engine
 * Press "3", [enter], modify the password of the Web Portal admin user
 * Press "4", [enter], initiazation the WGT_DOMAIN domain(ISO)
 * Press "5", [enter], modify the password of the Reports Portal admin user
 * Press "6", [enter], reset database password
 * Press "7", [enter], go back
```

    Engine Advanced Configuration
    
    
    1) Engine Cleanup 
    2) Engine Setup 
    3) Reset Web Portal 'admin' password 
    4) WGT_DOMAIN initialization
    5) Reset Reports Portal 'admin' user password
    6) Reset Database password
    7) Back
    
    
    Choose the advanced setting:
```

* Press "8", [enter], reboot or shutdown the system

```
    Restart or Shutdown the System.
    
    1) Restart the System 
    2) Shutdown the System
    3) Back
    
    Choose the advanced setting: 
```

* Press "9", [enter], get a shell

* Press "10", [enter], go back to view the summary information

* Press "11", [enter], get some help

* Press "12", [enter], logout
