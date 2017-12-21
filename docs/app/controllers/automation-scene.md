**Overview:** Controllers that handls scenes



**Author:** Martin Vach




* * *

# Global





* * *

## AutomationSceneController
Controller that handles list of scenes

### AutomationSceneController.loadScenes() 

Load schedules

**Returns**: `undefined`

### AutomationSceneController.runSceneTest(instance) 

Run test

**Parameters**

**instance**: `object`


### AutomationSceneController.activateScene(input, activeStatus) 

Activate

**Parameters**

**input**: `object`

**activeStatus**: `boolean`


### AutomationSceneController.cloneScene(input) 

Clone

**Parameters**

**input**: `object`

**Returns**: `undefined`

### AutomationSceneController.deleteScene() 

Delete



## AutomationSceneIdController
Controller that handles scene detail

### AutomationSceneIdController.resetModel() 

Reset model


### AutomationSceneIdController.loadInstance() 

Load instances


### AutomationSceneIdController.loadRooms() 

Load rooms


### AutomationSceneIdController.loadDevices() 

Load devices


### AutomationSceneIdController.uploadIcon(files, info) 

Validate an uploaded icon

**Parameters**

**files**: `object`

**info**: `object`

**Returns**: `undefined`

### AutomationSceneIdController.deleteIcon(string) 

Delete icon

**Parameters**

**string**: `string`

**Returns**: `undefined`

### AutomationSceneIdController.assignDevice(device) 

Assign device to a schedule

**Parameters**

**device**: `object`

**Returns**: `undefined`

### AutomationSceneIdController.unassignDevice(device) 

Remove device id from assigned device

**Parameters**

**device**: `object`


### AutomationSceneIdController.expandParams() 

Add or update device to the list (by type)


### AutomationSceneIdController.handleDevice() 

Add or update device to the list (by type)


### AutomationSceneIdController.handleSceneDevice() 

Add or update scene device


### AutomationSceneIdController.storeScene() 

Store


### AutomationSceneIdController.removeDeviceFromParams(device) 

Remove device from the params list

**Parameters**

**device**: `object`




* * *