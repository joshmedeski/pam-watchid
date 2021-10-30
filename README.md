PAM WatchID
-----------

A PAM plugin for authenticating using the new kLAPolicyDeviceOwnerAuthenticationWithBiometricsOrWatch API in macOS 10.15, written in Swift.

![demo](demo.gif)

Installation
------------

1. `$ sudo make install`
2. Edit `/etc/pam.d/sudo` to include as the first line: `auth sufficient pam_watchid.so "reason=execute a command as root"`

_Note that you might have other `auth`, don't remove them._

# Tasks

- [ ] Add badges to show what version of macOS is supported
- [ ] Add instructions full instructions for how to install (see my GitHub issue)
- [ ] Create checklist for how to update when a new version of macOS comes out  
