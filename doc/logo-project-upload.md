# Unloading configuration to PLC (LOGO!)

This software is installed as any typical application on windows machine. Nothing specific to tell here

Following are steps on how to upland configuration to LOGO!



Opening [project](https://github.com/austrisu/frostyICS/tree/main/config_files/logo!)

![image-20210504205144855](../doc/img/image-20210504205144855.png


![image-20210504205242134](../doc/img/image-20210504205242134.png)



Modifying IP address of target LOGO! if it is necessary:

![image-20210504205332650](../doc/img/image-20210504205332650.png)

![image-20210504205405309](../doc/img/image-20210504205405309.png)



If IP is changed Modbus and S7 partner devices need to be updated:

![image-20210504205545428](../doc/img/image-20210504205545428.png)



S7 configuration:

![image-20210504205704942](../doc/img/image-20210504205704942.png)



Uploading project to the  PLC:

![image-20210504205823986](../doc/img/image-20210504205823986.png)



Before uploading Soft Comfort will ask to search for device and choose to which of available devices to upload the project:

![image-20210504210022963](../doc/img/image-20210504210022963.png)



When project is downloaded to device you can see LOGO parameters on LOGO display and do some simple adjustments.

To debug the program if any changes are made can be done using built in tools. Online test allows to connect to PLC and check the status of program in the PLC

![image-20210504210553460](../doc/img/image-20210504210553460.png)