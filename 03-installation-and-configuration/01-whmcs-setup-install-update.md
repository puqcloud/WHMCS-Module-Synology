# WHMCS setup (install/update)

### Synology module **[WHMCS](https://puqcloud.com/whmcs-module-synology.php)**
#####  [Order now](https://puqcloud.com/whmcs-module-synology.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/) | [Community](https://community.puqcloud.com/)

## System requirements

| Requirement | Minimum version |
|-------------|-----------------|
| **PHP** | 7.4 or higher (7.4 / 8.1 / 8.2) |
| **WHMCS** | 8.x or higher |
| **ionCube Loader** | v13 or newer (v14, v15) |
| **Synology DSM** | 7.x or higher |

> **Note:** The module uses ionCube encoding. Make sure ionCube Loader is installed and active on your server.

---

## Backward compatibility

This module supports older PHP versions and older WHMCS versions for maximum compatibility with existing hosting environments. PHP-version-specific builds are provided:

- **PHP 7.4** — for legacy WHMCS 8 installations running PHP 7.4
- **PHP 8.1** — for WHMCS 8 installations running PHP 8.1
- **PHP 8.2** — for WHMCS 8/9 installations running PHP 8.2

Each build is encoded with the appropriate ionCube version for the target PHP runtime.

---

## Download

The module can be ordered and downloaded from PUQ Cloud:

- **Order / Download:** [https://puqcloud.com/whmcs-module-synology.php](https://puqcloud.com/whmcs-module-synology.php)
- **Community:** [https://community.puqcloud.com/](https://community.puqcloud.com/)
- **Direct download links for the latest version:**

```
# PHP 7.4
wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/php74/PUQ_WHMCS-Synology-latest.zip

# PHP 8.1
wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/php81/PUQ_WHMCS-Synology-latest.zip

# PHP 8.2
wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/php82/PUQ_WHMCS-Synology-latest.zip
```

After downloading, extract the archive:

```
unzip PUQ_WHMCS-Synology-latest.zip
```

---

## Installation

### Step 1: Upload files

Extract the module archive and copy the `puqSynology` directory to the WHMCS servers module directory:

```
WHMCS_WEB_DIR/modules/servers/puqSynology
```

### Step 2: Add server

Navigate to **System Settings** → **Servers** → **Add New Server**:

1. Enter the correct **Name** and **Hostname**
2. In Server Details, select the **PUQ Synology** module
3. Enter valid Synology DSM credentials (username and password)
4. Click **Test connection** to verify

### Step 3: Create product

Navigate to **System Settings** → **Products/Services** → **Create a New Product**:

1. Select the **PUQ Synology** module in the Module settings section
2. Configure the product parameters

---

## Update

### Step 1: Backup

Before updating, it is recommended to back up:
- WHMCS database
- Module files in `modules/servers/puqSynology/`

### Step 2: Upload new files

Download and extract the new version, then overwrite all files in:

```
WHMCS_WEB_DIR/modules/servers/puqSynology/
```

### Step 3: Verification

1. Log in to the WHMCS admin panel
2. Check the module is functioning correctly
3. Verify product settings

> **Important (v3.0):** Product reconfiguration is required after updating to version 3.0.
