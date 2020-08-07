#!/usr/bin/env bash
# Usage: bash uninstall_vmware.bash
remove() {
  entry="$1"

  echo -ne "Removing \e[1;34m$entry\e[0m... "
  sudo rm -rf "$entry" &> /tmp/uninstall-vmware.log

  if [[ ! -e "$entry" ]]; then
    echo -e "\e[1;32mOK\e[0m"
  else
    echo -e "\e[1;31mFAILED\e[0m"
  fi
}

remove "/Applications/VMware Fusion.app"
remove "/Library/Application Support/VMware"
remove "/Library/Application Support/VMware Fusion"
remove "/Library/Preferences/VMware Fusion"
remove "/private/var/root/Library/Logs/VMware"
remove "/private/var/db/vmware"
remove "/Library/Logs/VMware/"
remove "/private/var/run/vmware"
remove "/private/var/run/VMware Fusion Services.lock"
remove "/private/var/run/VMware Fusion Services.sock"
remove "/private/var/root/Library/Preferences/VMware Fusion"
remove "$HOME/Library/Application Support/VMware Fusion"
remove "$HOME/Library/Caches/com.vmware.fusion"
remove "$HOME/Library/Preferences/VMware Fusion"
remove "$HOME/Library/Logs/VMware"
remove "$HOME/Library/Preferences/VMware Fusion"
remove "$HOME/Library/Preferences/com.vmware.fusion.LSSharedFileList.plist"
remove "$HOME/Library/Preferences/com.vmware.fusion.plist"
remove "$HOME/Library/Preferences/com.vmware.fusionStartMenu.plist"
remove "$HOME/Library/Preferences/com.vmware.fusion.LSSharedFileList.plist"
remove "$HOME/Library/Preferences/com.vmware.fusion.LSSharedFileList.plist.lockfile"
remove "$HOME/Library/Preferences/com.vmware.fusion.plist"
remove "$HOME/Library/Preferences/com.vmware.fusion.plist.lockfile"
remove "$HOME/Library/Preferences/com.vmware.fusionDaemon.plist"
remove "$HOME/Library/Preferences/com.vmware.fusionDaemon.plist.lockfile"
remove "$HOME/Library/Preferences/com.vmware.fusionStartMenu.plist"
remove "$HOME/Library/Preferences/com.vmware.fusionStartMenu.plist.lockfile"

