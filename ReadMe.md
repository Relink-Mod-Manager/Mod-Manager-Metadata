# Relink Mod Manager - Metadata

This repo contains the metadata used by the [Relink Mod Manager](https://github.com/Relink-Mod-Manager/Relink-Mod-Manager) to control aspects such as informing users of new updates based on `LatestVersion.txt` content and important alerts/messages in `Alerts.json`.

`Alerts.json` has only a few basic components to it:
* `MaxVersionShown` - Alert will be displayed for the Mod Managers up to this version number.
* `Alert` - Alert text to display in the popup message.
* `Link` - Any http/https prefixed URL to allow directing users to. If no value is set, the link button will not be shown.