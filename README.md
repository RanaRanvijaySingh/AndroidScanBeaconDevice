AndroidScanBeaconDevice
=======================
This application show how to use your android set as a beacon scanner. You can find this application in the android sdk version 4.4 samples projects.<br />
<br />
To get started with the application you need to follow these steps.<br />
<br /><br />
* Give the permission in the manifest file along with that declare an activity and service.(AndroidManifest.xml)<br />
* Create a layout for the main screen to show number of available devices. (listitem_device.xml)<br />
* Create a layout for the beacon characteristics. (gatt_services_characteristics.xml)  <br />
* Create a layout to handle the action bar. (actionbar_indeterminate_progress.xml)<br />
* Write a main class. (DeviceScanActivity.java)<br />
* Write a device controller class. (DeviceControlActivity.java)<br />
* Write a service class. (BluetoothLeService.java)<br />
* Write a class  to store the Gatt attribute values. (SampleGattAttributes.java)<br />
