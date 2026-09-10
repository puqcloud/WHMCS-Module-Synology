# WHMCS Installation and Update

### Synology module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-synology.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/) | [Community](https://community.puqcloud.com/)

## System requirements

| Requirement | Minimum |
|-------------|---------|
| **WHMCS** | 8.x+, 9.x+. |
| **PHP** | 7.4, 8.1, 8.2, 8.3, 8.4 |
| **Synology DSM** | 7.x or higher |
| **ionCube Loader** | v15+ |

> **Note:** The module uses ionCube encoding. Make sure ionCube Loader is installed and active on your server.

---

## Download

> **Note:** The module now uses **ionCube 15**, which provides universal out-of-the-box support for all encodings across modern PHP runtimes.
>
> All versions can be found at this link:
> [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/)
>
> Older module versions for WHMCS 8 are available in the archive directory:
> [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/archive/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/archive/)

The module can be ordered and downloaded from PUQ Cloud:

- **Order Module:** [https://puqcloud.com/whmcs-module-synology.php](https://puqcloud.com/whmcs-module-synology.php)
- **Documentation:** [https://doc.puq.info/books/synology-whmcs-module](https://doc.puq.info/books/synology-whmcs-module)
- **All Versions / Download:** [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/)
- **Support:** [https://puqcloud.com/submitticket.php](https://puqcloud.com/submitticket.php?step=2&deptid=1)
- **Community:** [https://community.puqcloud.com/](https://community.puqcloud.com/)
- **Direct download link for the latest version:**

```bash
wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/PUQ_WHMCS-Synology-latest.zip
```

After downloading, extract the archive:

```bash
unzip PUQ_WHMCS-Synology-latest.zip
```

---

## Installation

### Step 1: Upload files

Extract the module archive and copy the `puqSynology` directory to the WHMCS servers module directory:

```bash
cp -r puqSynology /path/to/whmcs/modules/servers/
```

Or target path:
```
WHMCS_WEB_DIR/modules/servers/puqSynology
```

Once the files are uploaded, proceed to the WHMCS Setup Guide to configure the server and product.

---

## Update

The update procedure is the same as installation — replace the existing files with the new version:

1. Download the latest version as described in the Download section.
2. Unzip the archive.
3. Replace the existing `WHMCS_WEB_DIR/modules/servers/puqSynology` directory with the new one.
4. Verify the version number in the module interface matches the new release.
