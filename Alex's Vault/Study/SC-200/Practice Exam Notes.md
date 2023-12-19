To collect data in custom log formats in Microsoft Sentinel with the Azure Log Analytics Agent, the following must be done:
	1. Select Custom Logs from the log analytics workspace navigation Menu
	2. On the custom tables tab, click on Add custom log
	3. Add a sample log file from the device in the sample tab
	4. In the record delimiter tab, select either newline or timestamp delimiter
	5. In the collection paths tab, select a windows or linux path type then enter the path to the devices logs
	6. Give the log a custom name and then add a description

EVENTID 4624 = A logon session has been created on destination machine
EVENTID 4720 = A new user object has been created

The Azure Connected Machine agent enables you to manage your Windows and Linux machines hosted outside of Azure on your corporate network or other cloud providers.