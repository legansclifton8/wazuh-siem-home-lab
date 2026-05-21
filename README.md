<h1>Wazuh SIEM Monitoring & Threat Investigation Lab</h1>

<h2>Description</h2>
This project focused on building and configuring a Security Information and Event Management (SIEM) lab environment using Wazuh, Ubuntu Server, Windows 10, VirtualBox, PowerShell, and Windows Event Logs to simulate real-world SOC analyst monitoring, endpoint onboarding, authentication monitoring, and security event investigation workflows.

The lab environment was configured using Ubuntu Server hosted within VirtualBox to deploy the Wazuh SIEM platform. A Windows 10 endpoint agent was installed, configured, and connected to the Wazuh manager to generate and monitor Windows security events, authentication activity, and endpoint telemetry within a controlled virtualized environment.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Wazuh SIEM</b>
- <b>Ubuntu Server</b>
- <b>Windows 10</b>
- <b>VirtualBox</b>
- <b>PowerShell</b>
- <b>Windows Event Logs</b>
- <b>OpenSSH</b>
- <b>TCP/IP Networking</b>
- <b>Wazuh Agent</b>

<h2>Environments Used</h2>

- <b>Ubuntu Server Virtual Machine</b>
- <b>Windows 10 Virtual Machine</b>
- <b>VirtualBox Bridged Networking</b>

<h2>Project Walk-through:</h2>

<p align="center">

Enabled OpenSSH during Ubuntu Server configuration to allow secure remote management and administration access to the SIEM server environment: <br/>
<img src="https://i.imgur.com/bSQ0uJ8.png"/>
<br />
<br />

Verified successful internet connectivity from the Ubuntu Server virtual machine to confirm external network access required for package downloads and SIEM deployment: <br/>
<img src="https://i.imgur.com/mpYuRRq.png"/>
<br />
<br />

Updated Ubuntu Server repositories and installed required packages to prepare the Linux environment for Wazuh SIEM deployment and dependency installation: <br/>
<img src="https://i.imgur.com/StDlZlO.png" />
<br />
<br />

Downloaded the official Wazuh installation script from the Wazuh package repository in preparation for SIEM platform deployment: <br/>
<img src="https://i.imgur.com/UWJuDXU.png"/>
<br />
<br />

Encountered operating system compatibility validation warnings during Wazuh deployment and bypassed version checks to continue SIEM installation within the Ubuntu Server lab environment: <br/>
<img src="https://i.imgur.com/dddV8tW.png"/>
<br />
<br />

Configured VirtualBox networking settings and changed the virtual machine adapter to Bridged Adapter mode to allow communication between the Wazuh server and Windows endpoint: <br/>
<img src="https://i.imgur.com/1hHfo4C.png"/>
<br />
<br />

Accessed the Wazuh web dashboard through the browser using the SIEM server IP address to begin centralized monitoring configuration: <br/>
<img src="https://i.imgur.com/C5UojDO.png"/>
<br />
<br />

Verified successful deployment of the Wazuh SIEM dashboard and confirmed operational visibility into the centralized security monitoring environment: <br/>
<img src="https://i.imgur.com/IQwQSZm.png"/>
<br />
<br />

Installed and configured the Wazuh Windows endpoint agent to establish communication between the Windows endpoint and the Wazuh SIEM manager server: <br/>
<img src="https://i.imgur.com/9YtCSID.png"/>
<br />
<br />

Verified successful agent registration and active endpoint connectivity within the Wazuh SIEM dashboard, confirming centralized endpoint monitoring functionality: <br/>
<img src="https://i.imgur.com/aV2A913.png"/>
<br />
<br />

Simulated a failed authentication attempt using the Windows <code>runas</code> command to generate Windows security events and authentication alerts for SOC monitoring analysis: <br/>
<img src="https://i.imgur.com/aV2A913.png"/>
<br />
<br />

Investigated and analyzed authentication-related security alerts within the Wazuh SIEM dashboard, including failed login events mapped to MITRE ATT&CK techniques and detection rules: <br/>
<img src="https://i.imgur.com/mdkl0Ie.png"/>
<br />

<h2>Conclusion</h2>

This lab provided hands-on experience with SIEM deployment, endpoint onboarding, authentication monitoring, security event investigation, and centralized log analysis within a virtualized SOC environment. The project strengthened practical understanding of endpoint visibility, Windows event monitoring, alert investigation, agent troubleshooting, and real-world SOC analyst workflows using the Wazuh security platform.
