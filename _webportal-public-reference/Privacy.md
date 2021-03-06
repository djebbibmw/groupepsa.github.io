---
title: PRIVACY
supported:
  - 3
  - 4
type: class
---

#### EXAMPLE

Provides the methods to manage information about the privacy settings.

#### METHODS SUMMARY

Method | Response Type | Description
-----|----|----
[Privacy.Mode()]({{ site.baseurl }}/webportal/reference/#api-Privacy-Mode) | String | Get the privacy mode

#### MESSAGE SUMMARY

Message Type | Description
----|----
[Privacy.ModeFull]({{ site.baseurl }}/webportal/reference/#event-Privacy-ModeFull) | Triggered when the user switches to the most restrictive privacy mode.
[Privacy.ModeGeoloc]({{ site.baseurl }}/webportal/reference/#event-Privacy-ModeGeoloc) | Triggered when the user switches to the geolocation restricted mode.
[Privacy.ModePublic]({{ site.baseurl }}/webportal/reference/#event-Privacy-ModePublic) | Triggered when the user switches to the public privacy mode.
