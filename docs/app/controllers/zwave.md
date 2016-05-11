**Overview:** Controllers that handle Z-Wave devices actions.



**Author:** Martin Vach




* * *

# Global





* * *

## ZwaveSelectController
This is a new version of the ZwaveAddController and is not completed!!!

### ZwaveSelectController.loadProducts() 

Load products - vendor logos


### ZwaveSelectController.loadData() 

Load z-wave devices



## ZwaveAddController
The controller that renders Z-Wave manufacturers and devices.

### ZwaveAddController.loadData() 

Load z-wave devices



## ZwaveManageController
The controller that renders and handles data in the Z-Wave/Manage section.

### ZwaveManageController.setTab() 

Set tab


### ZwaveManageController.loadData() 

Load data


### ZwaveManageController.runZwaveCmd() 

Run zwave CMD


### ZwaveManageController.zwaveApiData() 

Get zwaveApiData


### ZwaveManageController.isInterviewDone() 

notInterviewDevices



## ZwaveInterviewController
The controller that handles interview process in the Z-Wave/Network section.

### ZwaveInterviewController.startConfiguration() 

Start configuration


### ZwaveInterviewController.cancelConfiguration() 

Cancel configuration


### ZwaveInterviewController.forceInterview() 

Force interview


### ZwaveInterviewController.resetConfiguration() 

Reset configuration


### ZwaveInterviewController.checkInterview() 

Check interview



## ZwaveInterviewController
The controller that handles Z-Wave exclusion process.

### ZwaveInterviewController.loadZwaveApiData() 

Load z-wave devices


### ZwaveInterviewController.refreshZwaveApiData() 

Refresh z-wave devices


### ZwaveInterviewController.runZwaveCmd() 

Run ExpertUI command


### ZwaveInterviewController.removeFailedNode() 

Run ExpertUI command - remove failed node



## ZwaveManageIdController
The controller that renders and handles configuration data for a single Z-Wave device.

### ZwaveManageIdController.allSettled() 

Load all promises


### ZwaveManageIdController.addRoom() 

Add room


### ZwaveManageIdController.updateAllDevices() 

Update all devices


### ZwaveManageIdController.zwaveConfigApiData() 

Get zwaveApiData




* * *