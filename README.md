# PhoneTrack ownCloud/Nextcloud application

[![Build status](https://gitlab.com/eneiluj/phonetrack-oc/badges/master/build.svg)](https://gitlab.com/eneiluj/phonetrack-oc/commits/master)
[![coverage report](https://gitlab.com/eneiluj/phonetrack-oc/badges/master/coverage.svg)](https://eneiluj.gitlab.io/phonetrack-oc/coverage/)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/phonetrack/localized.svg)](https://crowdin.com/project/phonetrack)

PhoneTrack is an app to get tracking information from mobile devices
and display them dynamically on a Leaflet map.

Go to [PhoneTrack Crowdin project](https://crowdin.com/project/phonetrack) if you want to help to translate this app in your language.

How to use PhoneTrack :

* create a tracking session
* give the tracking URL\* to the mobile devices. Choose the [logging method](https://gitlab.com/eneiluj/phonetrack-oc/wikis/userdoc#logging-methods) you prefer.
* Watch the session's devices positions in real time (or not) in PhoneTrack normal or public page

(\*) Don't forget to set the device name in the URL. Replace "yourname" with the desired device name. Setting the device name in logging app options only works with Owntracks, Traccar and OpenGTS.

On PhoneTrack main page, while watching a session, you can :

* edit/add/delete points
* restrict autozoom to some devices
* display position history display (path lines)
* rename a session/device
* change a device color, move it to another session
* share a session to other users (read-only)
* make a session public and share it via a public link. Positions are not visible in web logging page "publicWebLog" for private sessions.
* import/export a session in GPX format (one file with one track by device).
* display session statistics
* filter points
* [reserve a device name](https://gitlab.com/eneiluj/phonetrack-oc/wikis/userdoc#device-name-reservation) to make sure only authorized user can log with this name
* toggle session auto export (daily/weekly/monthly)

Public page works like main page except there is only one session displayed and there is no need to be logged in.

This app is tested with Owncloud 10/Nextcloud 12 with Firefox 56+ and Chromium.

This app is under development.

Link to Owncloud application website : https://marketplace.owncloud.com/apps/phonetrack

Link to Nextcloud application website : https://apps.nextcloud.com/apps/phonetrack

## Donation

I develop this app during my free time.

* [Donate on Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=66PALMY8SF5JE) (you don't need a paypal account)
* Bitcoin : 1FfDVdPK8mZHB84EdN67iVgKCmRa3SwF6r
* Monero : 43moCXnskkeJNf1MezHnjzARNpk2BRvhuRA9vzyuVAkTYH2AE4L4EwJjC3HbDxv9uRBdsYdBPF1jePLeV8TpdnU7F9FN2Ao

## Install

See the [AdminDoc](https://gitlab.com/eneiluj/phonetrack-oc/wikis/admindoc) for installation details.

## Known issues

**Warning** : PhoneTrack does not work with group restriction on it. See [admindoc](https://gitlab.com/eneiluj/phonetrack-oc/wikis/admindoc#warning).

Any feedback will be appreciated.
