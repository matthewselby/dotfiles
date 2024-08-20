### first run https://strap.mikemcquaid.com/
# https://github.com/MikeMcQuaid/strap

### add dotfiles GH repo
# https://github.com/mathiasbynens/dotfiles/blob/master/.macos

### install all google fonts
#  https://gist.github.com/keeferrourke/d29bf364bd292c78cf774a5c37a791db


### set cask install directory to shared applications directory
cask_args appdir: "/Applications"

### homebrew taps
tap "1password/tap"
#tap "buo/cask-upgrade"
tap "homebrew/bundle"
#tap "homebrew/cask-drivers"
tap "homebrew/cask-fonts"
tap "homebrew/cask-versions"
#tap "homebrew/services"

### Aggtool deps
brew "gnuplot"

### install stuffs via brew
brew "php"
brew "composer"
brew "curl"
brew "gh"
brew "jq"
brew "python@3.11"
brew "mackup"
brew "mas"
brew "node"
brew "pnpm"
brew "trash"
brew "yt-dlp"
brew "wget"
# ffmpeg with all options
ALL_FFMPEG_OPTIONS = `brew options ffmpeg | grep -vE '\s' | grep -- '--with-'`.gsub("--", "").split("\n")
brew "ffmpeg", args: ALL_FFMPEG_OPTIONS


### install apps
#cask "gas-mask"
cask "1Password"
cask "alfred"
cask "bartender"
#cask "behringer-x32-edit"
#cask "cleanmymac"
cask "google-chrome"
cask "imageoptim"
cask "istat-menus"
cask "iterm2"
cask "rocket"
#cask "spotify"
cask "visual-studio-code"
#cask "zoom"
cask ""
#cask "dropbox"
#cask "transmission"
cask "github"
#cask "reaper"
cask "notion"
cask "transmit"
cask "cyberduck"
#cask "intel-power-gadget"
cask "focus"
cask "logi-options-plus"
cask "local"
cask "local-beta"
#cask "vlc"
#cask "propresenter"
#cask "elgato-stream-deck"
cask "elgato-control-center"
cask "google-drive"
cask "insomnia"
cask "postman"
cask "firefox"
cask "firefox-developer-edition"
cask "sequel-ace"
cask "tableplus"
cask "docker"


### install fonts
# need to submit cmg sans or host it myself
#cask "font-cmg-sans"

### install all nerd fonts
# brew tap homebrew/cask-fonts
brew search '/font-.*-nerd-font/' | awk '{ print $1 }' | xargs -I{} brew install --cask {} || true

### install mac app store apps
brew "mas"
#mas "Fantastical", id: 435003921
mas "Pages", id: 409201541
mas "Numbers", id: 409203825
mas "Keynote", id: 409183694
mas "Slack", id: 803453959
mas "Disk Speed Test", id: 425264550
#mas "Remote Desktop", id: 409907375
mas "BetterSnapTool", id: 417375580
mas "Todoist", id: 585829637
#mas "Amphetamine", id: 937984704
#mas "Airmail", id: 918858936
mas "ColorSlurp", id: 1287239339
mas "Mactracker", id: 430255202
mas "EasyRes", id: 688211836
mas "Speedtest", id: 1153157709
#mas "Grammarly for Safari", id: 1462114288
mas "The Unarchiver", id: 425424353
#mas "Final Cut Pro", id: 424389933
#mas "Playback", id: 751755884


### install drivers
# thunderbolt dock network driver
#cask "asix-ax88179"
