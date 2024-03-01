## Will Umbrel Appstore
This Repository is an Alternative AppStore for Umbrel, the self-hosting service, without having to publish applications officially on [Umbrel Official Appstore](https://github.com/getumbrel/umbrel-apps).

It is intended for personal use only. I am in no way linked to the creators of the applications in this 'appstore'.

### Applications

The following applications are included:
- `Homepage` - A modern, fast, secure dashboard. Easily configurable via YAML files.
- `Pingvin Share` - A self-hosted file-sharing platform and alternative to WeTransfer.

### Utilisation
To add an app store:
```
sudo ~/umbrel/scripts/repo add https://github.com/WyliGr/Will-Umbrel-appstore.git

sudo ~/umbrel/scripts/repo update
```

To install an app from the app store
```
sudo ~/umbrel/scripts/app install will-APPNAME
```

To remove an app store:
```
sudo ~/umbrel/scripts/repo remove https://github.com/WyliGr/Will-Umbrel-appstore.git
```
