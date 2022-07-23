# New Mac Setup Reference

This file outlines the standard set of applications and configuration changes that I make on a new Mac or new install of MacOS.

## Applications

### Editors and Notes

- **Visual Studio Code**: This is a fantastic code editor and can be used as a local wiki as well for notes. <https://code.visualstudio.com/>
- **Things**: Used to track projects. <https://culturedcode.com/things/>

### Development
- **GIT**: Source control, interact with Git Hub. <https://git-scm.com/book/en/v2/Getting-Started-Installing-Git>

### Browsers

- **Firefox Browser**: A good all around browser that supports most things and is fairly secure. <https://www.mozilla.org/en-US/firefox/mac/>
  
### Security

- **Bitwarden**: An open source password vault with browser integrations and local vault storage. <https://bitwarden.com/download/>
- **Private Internet Access**: Affordable and secure (at time of writing) VPN. <https://www.privateinternetaccess.com/download/mac-vpn>

### Imaging

- **balenaEtcher**: A free utility for formatting and installing iso images onto flash storage. <https://www.balena.io/etcher/>
- **Raspberry PI Imager**: Used to image a rPI with built in images supported by the PI. <https://www.raspberrypi.com/software/>

### Chat and Communication

- **Discord**: Used for chat and screen sharing. <https://discord.com/download>

### MISC Tools

- **Amphetamine**: Program to control screen and sleep state of your Mac.  Useful for keep the screen on when using the laptop with a closed lid. <https://apps.apple.com/us/app/amphetamine/id937984704?mt=12>
- **Parcel**: Program to track packages and shipments. <https://parcelapp.net/>
- **Transmission**: Torrenting application. <https://transmissionbt.com/download/>
- **HomeBrew**: Homebrew installs the stuff you need that Apple (or your Linux system) didn’t.
  
    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

## Configuration Changes

### GIT

Run the following commands to properly configure Git for commits:

```bash
git config --global user.email "your.email"
git config --global user.name "your.github.username"
```
