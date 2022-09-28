### first run https://strap.mikemcquaid.com/
### https://github.com/MikeMcQuaid/strap

### add dotfiles GH repo
### https://github.com/mathiasbynens/dotfiles/blob/master/.macos

### install all google fonts
# curl https://raw.githubusercontent.com/qrpike/Web-Font-Load/master/install.sh | bash


### set cask install directory to shared applications directory
cask_args appdir: "/Applications"

### tap homebrew extras
tap "homebrew/cask"
tap "homebrew/cask-fonts"
tap "homebrew/cask-drivers"
tap "buo/cask-upgrade"


### install stuffs via brew
brew "gh"
brew "jq"
brew "node"
brew "pnpm"
brew "yt-dlp"
brew "wget"
brew "mackup"
brew "composer"
# ffmpeg with all options
ALL_FFMPEG_OPTIONS = `brew options ffmpeg | grep -vE '\s' | grep -- '--with-'`.gsub("--", "").split("\n")
brew "ffmpeg", args: ALL_FFMPEG_OPTIONS


### install apps
cask "gas-mask"
cask "1Password"
cask "alfred"
cask "bartender"
cask "behringer-x32-edit"
cask "cleanmymac"
cask "google-chrome"
cask "imageoptim"
cask "istat-menus"
cask "iterm2"
cask "rocket"
cask "spotify"
cask "visual-studio-code"
cask "zoom"
cask "cloudapp"
cask "dropbox"
cask "transmission"
cask "github"
cask "reaper"
cask "notion"
cask "transmit"
cask "sequel-pro"
cask "cyberduck"
cask "intel-power-gadget"
cask "focus"
cask "logi-options-plus"
cask "local"
cask "local-beta"
cask "vlc"
cask "propresenter"


### install mac app store apps
brew "mas"
mas "Fantastical - Calendar", id: 975937182
mas "Pages", id: 409201541
mas "Numbers", id: 409203825
mas "Keynote", id: 409183694
mas "Slack", id: 803453959
mas "Disk Speed Test", id: 425264550
mas "Remote Desktop", id: 409907375
mas "BetterSnapTool", id: 417375580
mas "Todoist", id: 585829637
mas "Amphetamine", id: 937984704
mas "Airmail", id: 918858936
mas "ColorSlurp", id: 1287239339
mas "Mactracker", id: 430255202
mas "EasyRes", id: 688211836
mas "Speedtest", id: 1153157709
mas "Grammarly: Writing App", id: 1462114288
mas "The Unarchiver", id: 425424353
mas "Final Cut Pro", id: 424389933
mas "Playback", id: 751755884


### install fonts
# need to submit cmg sans or host it myself
#cask "font-cmg-sans"


### install nerd fonts
cask "font-3270-nerd-font"
cask "font-fira-mono-nerd-font"
cask "font-inconsolata-go-nerd-font"
cask "font-inconsolata-lgc-nerd-font"
cask "font-inconsolata-nerd-font"
cask "font-monofur-nerd-font"
cask "font-overpass-nerd-font"
cask "font-ubuntu-mono-nerd-font"
cask "font-agave-nerd-font"
cask "font-arimo-nerd-font"
cask "font-anonymice-nerd-font"
cask "font-aurulent-sans-mono-nerd-font"
cask "font-bigblue-terminal-nerd-font"
cask "font-bitstream-vera-sans-mono-nerd-font"
cask "font-blex-mono-nerd-font"
cask "font-caskaydia-cove-nerd-font"
cask "font-code-new-roman-nerd-font"
cask "font-cousine-nerd-font"
cask "font-daddy-time-mono-nerd-font"
cask "font-dejavu-sans-mono-nerd-font"
cask "font-droid-sans-mono-nerd-font"
cask "font-fantasque-sans-mono-nerd-font"
cask "font-fira-code-nerd-font"
cask "font-go-mono-nerd-font"
cask "font-gohufont-nerd-font"
cask "font-hack-nerd-font"
cask "font-hasklug-nerd-font"
cask "font-heavy-data-nerd-font"
cask "font-hurmit-nerd-font"
cask "font-im-writing-nerd-font"
cask "font-iosevka-nerd-font"
cask "font-jetbrains-mono-nerd-font"
cask "font-lekton-nerd-font"
cask "font-liberation-nerd-font"
cask "font-meslo-lg-nerd-font"
cask "font-monoid-nerd-font"
cask "font-mononoki-nerd-font"
cask "font-mplus-nerd-font"
cask "font-noto-nerd-font"
cask "font-open-dyslexic-nerd-font"
cask "font-profont-nerd-font"
cask "font-proggy-clean-tt-nerd-font"
cask "font-roboto-mono-nerd-font"
cask "font-sauce-code-pro-nerd-font"
cask "font-shure-tech-mono-nerd-font"
cask "font-space-mono-nerd-font"
cask "font-terminess-ttf-nerd-font"
cask "font-tinos-nerd-font"
cask "font-ubuntu-nerd-font"
cask "font-victor-mono-nerd-font"


### install drivers
# thunderbolt dock network driver
cask "asix-ax88179"
