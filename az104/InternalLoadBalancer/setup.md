Internal Load Balancer Demo

These ARM templates will create the lab environment used to demonstrate creating and configuring an Azure internal load balancer.  
The first template, 1-internal-lb-rg-setup, will create a resource group where the lab objects will be created. The resource group will be named rg-ilb-eus.
The second template, 2-internal-lb-lab-setup.json, will create the lab infrastructure. 

To create the resource group: 
  1.	Copy the contents of 1-internal-lb-rg-setup.json
  2.	Sign into the Azure portal
  3.	Search for deploy, and select Deploy a custom template
  4.	Select Build your own template in the editor
  5.	Delete the existing content from the Edit template window
  6.	Paste the contents of 1-internal-lb-rg-setup.json
  7.	Click Save
  8.	Verify the correct subscription is selected
  9.	Click Review + create
  10.	Verify the validation passed and click Create
  11.	Verify the deployment completed successfully

To create the lab infrastructure:
  1.	Copy the contents of 2-internal-lb-lab-setup.json
  2.	Sign into the Azure portal
  3.	Search for deploy, and select Deploy a custom template
  4.	Select Build your own template in the editor
  5.	Delete the existing content from the Edit template window
  6.	Paste the contents of 2-internal-lb-lab-setup.json
  7.	Click Save
  8.	Verify the correct subscription is selected
  9.	Select the resource group created earlier (or create a new one if you skipped the first template)
  10.	Modify the default parameters if necessary, for your environment
  11.	Provide a username and password for the admin account for the VMs
  12.	Click Review + create
  13.	Verify the validation passed and click Create
  14.	Verify the deployment completed successfully
