# Network Automation - Cisco Catalyst Center Sandbox

## Provisioning Sandbox Catalyst Center

Visit the website https://developer.cisco.com/site/sandbox.

Navigate to **Launch Sandbox** and create a Cisco Account.
Select **Launch** on **Catalyst Center Sandbox**. This process will take 1 hour (more details in the E-Mail).
When the Sandbox is ready, you will receive an E-Mail how to connect to your sandbox. You need the **Cisco AnyConnect Secure Client** on your computer and configure it with the credentials in the E-Mail.

Click on the **Catalyst Center Sandbox lab**-Link. Now you see your resources. Copy the IP Address of the dnacenter resource in your browser for your Catalyst Center GUI.

## Connection from ansible controler to the sandbox api

It's important to user **ansible_connection: local** in your inventory. You are not able to connect via SSH on the managed nodes because your network device has no python packages installed.



