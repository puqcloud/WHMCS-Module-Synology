# Changelog

### Synology module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-synology.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/) | [Community](https://community.puqcloud.com/)

---

##### v3.0 Released 28-06-2026

**A major release — the module has been fully re-engineered and adapted to the latest Synology DSM.**

- **Full support for the entire Synology DSM 7 line (up to and including the latest DSM 7.2+).**
  The whole DSM Web API integration was reworked and verified against current DSM: token-based session
  authentication (SID + SynoToken), correct user **group-membership** management, and live disk-quota
  statistics.
- **Reliable account lifecycle** — create, suspend, unsuspend, terminate, change password and change
  package — all aligned with the current `SYNO.Core.*` APIs.
- **Server-side group assignment.** Provisioned users are added to a **pre-configured Synology group**,
  chosen from a drop-down that is populated live with the groups that actually exist on your server.
  The real disk/permission limits are enforced by that Synology group.
- **New product configuration UI.** A dynamic "Module Settings" panel on the product page (JSON-based),
  which also keeps working on older WHMCS versions.
- **DSM-policy-aware password generation** (automatically matches your server's password-strength rules)
  and flexible **macro-based username rules** with collision protection.
- **Protection against duplicates** — the module never overwrites an account that already exists on Synology.
- **Redesigned client area** — modern cards, copy-to-clipboard for credentials, show/hide password,
  disk-usage pie chart and 30-day / monthly history charts.
- **25 interface languages.**
- **Broad compatibility** — PHP 7.4 / 8.1 / 8.2 and older WHMCS releases (per-PHP builds provided).
- **Hardened & maintainable** — comprehensive error handling and logging, safe data access throughout,
  and built-in license verification with proactive admin alerts.

> **Note:** Product reconfiguration is required after updating to v3.0 — product settings have moved to
> the new Module Settings UI.

---

##### v1.2.1 Released 02-04-2023

1. Adaptation for Synology DSM 7.1.1

---

##### v1.2 Released 05-03-2023

1. Support for PHP 8.1 and PHP 7.4
2. Support for Synology DSM 6.x and Synology DSM 7.x
3. Changes made to templates, add icons
4. API timeout set to 30

---

##### v1.1 Released 23-01-2023

1. Support WHMCS V8.6
2. Support IonCube PHP Loader v12
3. Support for PHP 8.1
4. Changes made to templates
5. In the service settings, the choice of email template was changed to a drop-down menu
6. Added translations: German, Ukrainian

---

##### v1.0 Released 01-08-2022

First version
