---
uuid: 20230425121339
created: 2023-04-25T12:13:39
last-modified: 2023-04-25T12:13:39
alias:
---


# [[Setting up new MacBook]]

## Misc:
- Log in to:
	- ICloud
	- Accounts in Mail & Calendar
	- Accounts in Google Suite
	- Github
		- [Generate ssh key and add to agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
		- Modify `~/.ssh/config` if necessary
	- Modify `/etc/hosts` if necessary
	- [Zoho Invoice](https://www.zoho.com/invoice/)

## Main Installs:
- Homebrew
	- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
	- Homebrew installs git and xcode tools automatically
- [Google Chrome](https://www.google.com/chrome/)
- [1Password](https://1password.com/downloads/mac/)
	- [Chrome Extension](https://chrome.google.com/webstore/detail/1password-%E2%80%93-password-mana/aeblfdkhhhdcdjpifhhbdiojplfjncoa/related)
- [JetBrains Intellij IDEA](https://www.jetbrains.com/idea/download/download-thanks.html)
- [Slack](https://slack.com/downloads/instructions/mac)
- [Tailscale VPN](https://tailscale.com/download/)
- [Endpoint Verification Chrome extension](https://chrome.google.com/webstore/detail/endpoint-verification/callobklhcbilhphinckomhgkigmfocg/related?hl=en)
- Java 17
	- `brew install openjdk@17`
- Maven
	- brew install maven

## CLI Tools:
- Iterm2
	- `brew install --cask iterm2`
	- `Preferences -> Keys -> HotKey -> Create Dedicated Hotkey Window ->  §`
	- `Preferences -> Profiles -> Keys -> Key Mappings -> Presets... -> Natural Text Editing`
- Oh My Zsh and powerlevel10k theme
	- `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
	- `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`
- `brew install kubectl`
- `brew install minikube`
- `brew install helm`
- `brew install localtunnel`
- `brew install azure-cli`
- `brew install awscli`
- `brew install npm`
- `npm install -g @angular/cli`

## Specific Installs:
- Project specific 
	- [Microsoft Teams](https://www.microsoft.com/en/microsoft-teams/download-app#for-desktop1)
	- [FortiClient VPN](https://www.fortinet.com/support/product-downloads)
	- [Devolutions Remote Desktop Manager](https://devolutions.net/remote-desktop-manager)
	- [Azure Data Studio](https://learn.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver16&tabs=redhat-install%2Credhat-uninstall)
	- Windows VM
		- [VMWare Fusion Player Personal](https://customerconnect.vmware.com/evalcenter?p=fusion-player-personal-13)
		- https://www.youtube.com/watch?v=za2CyrxKYFs
		- [Microsoft Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)
		- https://tech.namshi.io/blog/2015/08/02/vmware-fusion-headless/
- Dev tools
	- [Microsft VSCode](https://code.visualstudio.com/)
	- [Zed Editor](https://zed.dev/download)
	- [Docker](https://www.docker.com/)
	- [K8S Lens](https://k8slens.dev/)
- Productivity
	- [Raycast](https://www.raycast.com/)
	- [Rectangle](https://rectangleapp.com/)
	- [BetterTouchTool](https://folivora.ai/downloads/)
	- [Swish](https://highlyopinionated.co/swish/)
	- [HyperKey](https://hyperkey.app/)
	- [Paletro](https://appmakes.io/paletro)
	- [Mission Control Plus](https://www.fadel.io/missioncontrolplus)
	- [Shottr](https://shottr.cc/)
	- [HazeOver](https://hazeover.com/)
	- [Centered](https://www.centered.app/)
- Reading, Archiving & Notes
	- [Obsidian](https://obsidian.md/download)
	- [Drafts](https://getdrafts.com/)
	- [Raindrop.io](https://raindrop.io/download)
	- [Omnivore app](https://omnivore.app/)
	- [Hyperduck](https://sindresorhus.com/hyperduck)
	- [OwlOCR](https://owlocr.com/)
- Misc
	- Logi Options+
	- [App Tamer](https://www.stclairsoft.com/AppTamer/)
	- [MeetingBar](https://github.com/leits/MeetingBar)
	- [Arc Browser](https://arc.net/)
	- [AppCleaner](https://freemacsoft.net/appcleaner/)
	- [Latest](https://github.com/mangerlahn/Latest)
	- [HiddenBar](https://apps.apple.com/us/app/hidden-bar/id1452453066?mt=12)
	- [Presentify](https://presentify.compzets.com/)
	- [QuickGPT](https://sindresorhus.gumroad.com/l/quickgpt)
	- [Microsoft Edge](https://www.microsoft.com/en-gb/edge/download?form=MA13FJ)
	- [Keka](https://www.keka.io/en/)

## Settings
- Turn off:
	- Desktop & Dock
		- Automatically rearrange Spaces based on most recent use
		- Hot Corners
	- Displays
		- Auto adjust brightness
		- True Tone
- Appearance:
	- Show Scroll bars - always
	- Click in the scroll bar to - jump to the spot that's clicked
- Control Center:
	- Show Battery Percentage
	- Bluetooth - Show in Menu Bar
- Trackpad
	- Tap to Click on

---

## 📇 Additional Metadata

- 🗂 Type:: #type/note
- #inbox 
