*THIS REPOSITORY IS OBSOLETE, BUILDBOT IS NOT USED ANY LONGER*
==============================================================

Buildbot Configuration for wxWidgets
====================================

Overview
--------

This repository contains the configuration of [Buildbot](http://buildbot.net/)
running at http://buildbot.tt-solutions.com/wx/.

Secret Passwords
----------------

The master configuration file includes `passwd.cfg` which is supposed to
contain the following information:
```py
slaves = {
    "slave1_name": "slave1_password",
    ...
}

github_secret = "secret for GitHub web hook"
```
