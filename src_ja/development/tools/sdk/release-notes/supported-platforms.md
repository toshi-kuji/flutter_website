---
title: Supported platforms
short-title: Supported platforms
description: The platforms that Flutter supports by platform version.
---

## Supported platforms

As of the current release,
Flutter supports the following platforms:

|Platform|Version                       |Channels |
|--------|------------------------------|---------|
|Android | API 19 & above               | All     |
|iOS     | iOS 9 & above                | All     |
|Linux   | Debian 10 & above            | All     |
|macOS   | El Capitan & above           | All     |
|Web     | Chrome 84  & above           | All     |
|Web     | Firefox 72.0 & above         | All     |
|Web     | Safari on El Capitan & above | All     |
|Web     | Edge 1.2.0 & above           | All     |
|Windows | Windows 10 & above           | All     |

All channels include master, beta,
and stable channels. 

{{site.alert.note}}
  The dev channel is retired. For more information,
  refer to [What's new in Flutter 2.8][].
{{site.alert.end}}

[What's new in Flutter 2.8]: {{site.medium}}/flutter/whats-new-in-flutter-2-8-d085b763d181

## How we define a supported platform

We define three tiers of support for the platforms on
which Flutter runs:

1. Supported Google-tested platforms,
   which are platforms the Flutter team at 
   Google tests in continuous integration at every commit. 
1. Best effort platforms, supported through community
   testing, are platforms we believe we support through
   coding practices and ad-hoc testing,
   but rely on the community for testing.
1. Unsupported platforms, which are platforms that
   might work, but that the development team
   doesn't directly test or support.

### Supported Google-tested platforms

|Platform|Version               |
|--------|----------------------|
|Android |Android SDK 30        |
|Android |Android SDK 29        |
|Android |Android SDK 28        |
|Android |Android SDK 27        |
|Android |Android SDK 26        |
|Android |Android SDK 25        |
|Android |Android SDK 24        |
|Android |Android SDK 23        |
|Android |Android SDK 22        |
|Android |Android SDK 21        |
|Android |Android SDK 19        |
|iOS     |14-15                 |
|Web     |Chrome 84             |
|Web     |Firefox 72.0          |
|Web     |Safari / Catalina     |
|Web     |Edge 1.2.0            |
|Windows |Windows 10            |
|macOS   |El Capitan & greater  |
|Linux   |Debian 10             |

Note that Android SDK 20 is covered by
testing Android SDK 19, as the differences
between the two platform versions are minimal.

### Best effort platforms tested by the community

|Platform|Version       |
|--------|---------------|
|Android |Android SDK 20 |
|Android |Android SDK 18 |
|Android |Android SDK 17 |
|Android |Android SDK 16 |
|iOS     |iOS 9-13       |
|Windows |Windows 8      |
|Windows |Windows 7      |
|Linux   |Debian & below |

### Unsupported platforms

|Platform|Version                                     |
|--------|--------------------------------------------|
|Android |Android SDK 18 & below                      |
|iOS     |[iOS 8][] & below and [`arm7v` 32-bit iOS][]|
|Windows |Windows Vista & below                       |
|Windows |Any 32-bit platform                         |
|macOS   |Yosemite & below                            |

[iOS 8]: {{site.url}}/go/rfc-ios8-deprecation
[`arm7v` 32-bit iOS]: {{site.url}}/go/rfc-32-bit-ios-unsupported
