# Synology part setup guide

### Synology module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-synology.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/) | [Community](https://community.puqcloud.com/)

Here are the initial steps of configuring Synology devices to prepare them for use with the WHMCS module.

> **Note:** At the beginning, you should prepare the appropriate domain with the correct DNS entries so that you can generate a correct SSL certificate for Your Synology NAS server. 

##### 1. Generate an SSL certificate for your domain.

Connect the certificate for all services that will be used in the server.(FTPS, System, Synology Drive, etc...)

![04-synology-setup-1.png](../img/04-synology-setup-1.png)

##### 2. Make sure the partition is formatted in BTRFS

![07-synology-setup-4.png](../img/07-synology-setup-4.png)

##### 3. Enable the user's home folder.

![08-synology-setup-5.png](../img/08-synology-setup-5.png)

##### 4. Enable all necessary file services (ie: FTP, FTPS, SFTP, etc.).

![09-synology-setup-6.png](../img/09-synology-setup-6.png)

##### 5. Create user groups with the necessary quotas and permissions.

![05-synology-setup-2.png](../img/05-synology-setup-2.png)

![06-synology-setup-3.png](../img/06-synology-setup-3.png)