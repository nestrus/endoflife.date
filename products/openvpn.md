---
title: OpenVPN
category: app
iconSlug: openvpn
permalink: /openvpn
releasePolicyLink: https://community.openvpn.net/openvpn/wiki/SupportedVersions
changelogTemplate: https://github.com/OpenVPN/openvpn/blob/release/__RELEASE_CYCLE__/ChangeLog
releaseDateColumn: true

auto:
  methods:
  -   git: https://github.com/OpenVPN/openvpn.git

identifiers:
  - repology: openvpn

releases:
-   releaseCycle: "2.6"
    releaseDate: 2023-01-25
    eol: false
    latest: "2.6.0"
    latestReleaseDate: 2023-01-25

-   releaseCycle: "2.5"
    releaseDate: 2020-10-27
    eol: false
    latest: "2.5.10"
    latestReleaseDate: 2024-03-21

-   releaseCycle: "2.4"
    releaseDate: 2016-12-16
    eol: true
    latest: "2.4.12"
    latestReleaseDate: 2022-03-17

-   releaseCycle: "2.3"
    releaseDate: 2013-01-02
    eol: true
    latest: "2.3.18"
    latestReleaseDate: 2017-09-25

-   releaseCycle: "2.2"
    releaseDate: 2011-04-21
    eol: true
    latest: "2.2.3"
    latestReleaseDate: 2014-11-30

-   releaseCycle: "2.1"
    releaseDate: 2009-12-11
    eol: true
    latest: "2.1.4"
    latestReleaseDate: 2010-11-04

---

> [OpenVPN](https://openvpn.net/) is a widely used virtual private networking system.

OpenVPN Community Edition aka OpenVPN is a GPLv2 server and client.
OpenVPN Access Server (OpenVPN-AS) provides additional paid and proprietary features.
There is a strict dependency on [OpenSSL](https://endoflife.date/openssl) which is defined at the bottom of their version table page.