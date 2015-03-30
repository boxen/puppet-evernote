**This Boxen module is now deprecated. The advised method for installing applications with Boxen is to now use [homebrew-cask](http://caskroom.io/). Add the following to your manifest to install Evernote using brewcask:**

```puppet
package { 'evernote': provider => 'brewcask' }
```

---

# Evernote Puppet Module for Boxen

[![Build Status](https://travis-ci.org/boxen/puppet-evernote.png?branch=master)](https://travis-ci.org/boxen/puppet-evernote)

## Usage

To use the latest version of Evernote:
```puppet
include evernote
```

To use a specific version of Evernote:
```puppet
class { 'evernote':
  sourceUri => 'https://cdn1.evernote.com/mac-smd/public/Evernote_RELEASE_5.6.0_450741.dmg'
}
```


## Required Puppet Modules

* boxen

