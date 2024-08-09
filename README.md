# DOMAIN-ONLY Filter Lists
**Last Updated:** 2024-08-09 16:14:00

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [AdAway Blocklist](#adaway-blocklist-domains-only) (Domains-only)
  - [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) (Domains-only)
  - [Yoyos Hosts](#yoyos-hosts-domains-only) (Domains-only)
  - [AdRules DNS List](#adrules-dns-list-domains-only) (Domains-only)
  - [AdGuard DNS Filter](#adguard-dns-filter-domains-only) (Domains-only)
  - [EasyList](#easylist-domains-only) (Domains-only)
  - [EasyPrivacy](#easyprivacy-domains-only) (Domains-only)
  - [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) (Domains-only)
  - [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) (Domains-only)
  - [EasyList China](#easylist-china-domains-only) (Domains-only)
  - [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) (Domains-only)
  - [AWAvenue Adblock Rule](#awavenue-adblock-rule-domains-only) (Domains-only)
  - [OISD Small](#oisd-small-domains-only) (Domains-only)
  - [OISD Big](#oisd-big-domains-only) (Domains-only)
  - [ADgk](#adgk-domains-only) (Domains-only)
  - [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) (Domains-only)
  - [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) (Domains-only)
  - [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) (Domains-only)
  - [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) (Domains-only)
  - [d3Host List by d3ward](#d3host-list-by-d3ward-domains-only) (Domains-only)
  - [NoCoin Filter](#nocoin-filter-domains-only) (Domains-only)
  - [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) (Domains-only)
  - [DDNS Filter](#ddns-filter-domains-only) (Domains-only)
  - [IPFS Filter](#ipfs-filter-domains-only) (Domains-only)
  - [Anti SafeSearch Bypass](#anti-safesearch-bypass-domains-only) (Domains-only)
  - [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) (Domains-only)
  - [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) (Domains-only)
  - [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) (Domains-only)
  - [Anti Cellular Identity](#anti-cellular-identity-domains-only) (Domains-only)
- [License](#license)
- [Reporting Conversion Issues](#reporting-conversion-issues)

&nbsp;

# Details:
These are "DOMAIN-ONLY" **converted** versions of various popular original filter / blocking lists.
They have been modified from their original versions by scripts at: https://github.com/justdomains/ci

The scripts output **only** the full-domain-blocking entries from the original lists, while attempting to filter any domains that conflict with an exception rule on the original list.

**Because these are automated, converted _subsets_ of the original lists, please do not report omissions from these converted files to the list originator.**

&nbsp;

# Usage:
These converted files can be used with various DNS and domain-blocking tools:

## Using with [Pi-Hole](https://pi-hole.net/):
1. Copy the link to the Pi-Hole format for the desired list (from the appropriate table below).
2. [Add the URL to your Pi-Hole's block lists (**Settings** > **Pi-Hole's Block Lists**).](https://github.com/pi-hole/pi-hole/wiki/Customising-Sources-for-Ad-Lists)

## Using with other tools:
The converted lists are provided in a "Raw Domain List" format that contains only domains, one per line. Many other tools / scripts can ingest this format to add them to your blocklist.

&nbsp;

# The Lists:

| Converted List | License | Domains | Domain List | Last Updated |
:- | - | - | :-: | - |
| [AdAway Blocklist](#adaway-blocklist-domains-only) | [CC BY 3.0](https://github.com/AdAway/AdAway/blob/master/LICENSE) | 6540 | [**Download**](https://mili-tan.github.io/justdomains/lists/adaway.list) |  |
| [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) | MIT | 164643 | [**Download**](https://mili-tan.github.io/justdomains/lists/stevenblack.list) | 08 August 2024 13:24:29 (UTC) |
| [Yoyos Hosts](#yoyos-hosts-domains-only) | MCRAE GENERAL PUBLIC LICENSE | 3555 | [**Download**](https://mili-tan.github.io/justdomains/lists/yoyo.list) |   Thu, 08 Aug 2024 10:34:44 GMT |
| [AdRules DNS List](#adrules-dns-list-domains-only) | WTFPL | 122347 | [**Download**](https://mili-tan.github.io/justdomains/lists/adrules.list) |  |
| [AdGuard DNS Filter](#adguard-dns-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 66972 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2024-08-09T12:01:29.831Z |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 41977 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 09 Aug 2024 12:39 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 45036 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 09 Aug 2024 12:39 UTC |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 149 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2024/08/06 07:56 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](https://easylist.to/pages/licence.html) | 829 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 09 Aug 2024 12:39 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 5220 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 09 Aug 2024 16:01 UTC |
| [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 42965 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AWAvenue Adblock Rule](#awavenue-adblock-rule-domains-only) | CC BY-NC-SA 4.0 | 611 | [**Download**](https://mili-tan.github.io/justdomains/lists/awavenue.list) | 2024-07-23T09:36:03.160610+00:00 |
| [OISD Small](#oisd-small-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 44979 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) | 2024-08-09T15:07:26+0000 |
| [OISD Big](#oisd-big-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 173747 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdbig.list) | 2024-08-09T15:07:19+0000 |
| [ADgk](#adgk-domains-only) | MIT | 3135 | [**Download**](https://mili-tan.github.io/justdomains/lists/adgk.list) |  |
| [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 67848 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi.list) | 09 Aug 2024 00:05 UTC |
| [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 143029 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) | 09 Aug 2024 00:15 UTC |
| [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) | GPL2 | 151565 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7.list) |  |
| [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) | GPL2 | 37600 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7l.list) |  |
| [d3Host List by d3ward](#d3host-list-by-d3ward-domains-only) | CC BY-NC-SA | 131 | [**Download**](https://mili-tan.github.io/justdomains/lists/d3.list) |  |
| [NoCoin Filter](#nocoin-filter-domains-only) | [MIT](https://mit-license.org/) | 409 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 12 April 2023 |
| [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 3072 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) | 07 Aug 2024 22:11 UTC |
| [DDNS Filter](#ddns-filter-domains-only) | Unlicense | 35457 | [**Download**](https://mili-tan.github.io/justdomains/lists/ddns.list) |  |
| [IPFS Filter](#ipfs-filter-domains-only) | MIT | 77 | [**Download**](https://mili-tan.github.io/justdomains/lists/ipfs.list) |  |
| [Anti SafeSearch Bypass](#anti-safesearch-bypass-domains-only) | Unlicense | 234 | [**Download**](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |  |
| [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) | MIT | 97 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |  |
| [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) | GPL2 | 165 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |  |
| [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) | GPL3 | 24 | [**Download**](https://mili-tan.github.io/justdomains/lists/httpdns.list) |  |
| [Anti Cellular Identity](#anti-cellular-identity-domains-only) | GPL3 | 6 | [**Download**](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |  |

&nbsp;

## AdAway Blocklist (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |
| Pi-Hole | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |

**Source:** [https://adaway.org/hosts.txt](https://adaway.org/hosts.txt)

**Conversion Details:**
```
Total Lines Processed: 10607
Comment Lines: 2042
Empty Lines: 2023
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 2
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 6540
```

&nbsp;

## StevenBlack's Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [stevenblack.list](https://mili-tan.github.io/justdomains/lists/stevenblack.list) |
| Pi-Hole | [stevenblack.list](https://mili-tan.github.io/justdomains/lists/stevenblack.list) |

**Source:** [https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts)
- Title: StevenBlack/hosts
- Last Modified: 08 August 2024 13:24:29 (UTC)

**Conversion Details:**
```
Total Lines Processed: 171319
Comment Lines: 4205
Empty Lines: 2459
Invalid Lines: 0
Non-Loopback Lines (Ignored): 7
Local Hosts (Ignored): 4
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 164643
```

&nbsp;

## Yoyos Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |
| Pi-Hole | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |

**Source:** [https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)
- Last Modified:   Thu, 08 Aug 2024 10:34:44 GMT

**Conversion Details:**
```
Total Lines Processed: 3569
Comment Lines: 14
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 3555
```

&nbsp;

## AdRules DNS List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adrules.list](https://mili-tan.github.io/justdomains/lists/adrules.list) |
| Pi-Hole | [adrules.list](https://mili-tan.github.io/justdomains/lists/adrules.list) |

**Source:** [https://raw.githubusercontent.com/Cats-Team/AdRules/main/dns.txt](https://raw.githubusercontent.com/Cats-Team/AdRules/main/dns.txt)
- Title: AdRules DNS List
- Homepage: [https://github.com/Cats-Team/AdRules](https://github.com/Cats-Team/AdRules)

**Conversion Details:**
```
Total Lines Processed: 122676
Comment Lines: 7
Empty Lines: 0
Non-Domain-only Rules Excluded: 322
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 122347
```

&nbsp;

## AdGuard DNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.69.2
- Last Modified: 2024-08-09T12:01:29.831Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 68948
Comment Lines: 1293
Empty Lines: 0
Non-Domain-only Rules Excluded: 624
Domain-only Rules Excluded (unsupported options): 4
Domain-only Rules Excluded (exception conflict): 55
Domain-only Rules Output: 66972
```

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202408091239
- Last Modified: 09 Aug 2024 12:39 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 74296
Comment Lines: 276
Empty Lines: 0
Non-Domain-only Rules Excluded: 26766
Domain-only Rules Excluded (unsupported options): 5211
Domain-only Rules Excluded (exception conflict): 66
Domain-only Rules Output: 41977
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202408091239
- Last Modified: 09 Aug 2024 12:39 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 53384
Comment Lines: 568
Empty Lines: 1
Non-Domain-only Rules Excluded: 7413
Domain-only Rules Excluded (unsupported options): 197
Domain-only Rules Excluded (exception conflict): 170
Domain-only Rules Output: 45036
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202408060756
- Last Modified: 2024/08/06 07:56 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1832
Comment Lines: 20
Empty Lines: 0
Non-Domain-only Rules Excluded: 1654
Domain-only Rules Excluded (unsupported options): 8
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 149
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202408091239
- Last Modified: 09 Aug 2024 12:39 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 49067
Comment Lines: 1276
Empty Lines: 0
Non-Domain-only Rules Excluded: 46852
Domain-only Rules Excluded (unsupported options): 67
Domain-only Rules Excluded (exception conflict): 43
Domain-only Rules Output: 829
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202408091601
- Last Modified: 09 Aug 2024 16:01 UTC
- Homepage: [https://github.com/easylist/easylistchina/](https://github.com/easylist/easylistchina/)

**Conversion Details:**
```
Total Lines Processed: 18614
Comment Lines: 108
Empty Lines: 0
Non-Domain-only Rules Excluded: 13114
Domain-only Rules Excluded (unsupported options): 160
Domain-only Rules Excluded (exception conflict): 12
Domain-only Rules Output: 5220
```

&nbsp;

## AdGuard Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.73.27
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 87284
Comment Lines: 3140
Empty Lines: 0
Non-Domain-only Rules Excluded: 40464
Domain-only Rules Excluded (unsupported options): 433
Domain-only Rules Excluded (exception conflict): 282
Domain-only Rules Output: 42965
```

&nbsp;

## AWAvenue Adblock Rule (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |
| Pi-Hole | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |

**Source:** [https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- Title: AWAvenue Ads Rule
- Version: 1.5.0-release-Patch-2
- Last Modified: 2024-07-23T09:36:03.160610+00:00

**Conversion Details:**
```
Total Lines Processed: 636
Comment Lines: 7
Empty Lines: 3
Non-Domain-only Rules Excluded: 18
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 611
```

&nbsp;

## OISD Small (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |
| Pi-Hole | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |

**Source:** [https://small.oisd.nl](https://small.oisd.nl)
- Title: oisd small
- Version: 202408091507
- Last Modified: 2024-08-09T15:07:26+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 44992
Comment Lines: 11
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 44979
```

&nbsp;

## OISD Big (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |
| Pi-Hole | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |

**Source:** [https://big.oisd.nl](https://big.oisd.nl)
- Title: oisd big
- Version: 202408091507
- Last Modified: 2024-08-09T15:07:19+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 173760
Comment Lines: 11
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 173747
```

&nbsp;

## ADgk (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adgk.list](https://mili-tan.github.io/justdomains/lists/adgk.list) |
| Pi-Hole | [adgk.list](https://mili-tan.github.io/justdomains/lists/adgk.list) |

**Source:** [https://raw.githubusercontent.com/banbendalao/ADgk/master/ADgk.txt](https://raw.githubusercontent.com/banbendalao/ADgk/master/ADgk.txt)
- Title: adgk鎵嬫満鍘诲箍鍛婅鍒
- Version: 20230323162617
- Homepage: [https://github.com/banbendalao/ADgk](https://github.com/banbendalao/ADgk)

**Conversion Details:**
```
Total Lines Processed: 9158
Comment Lines: 4
Empty Lines: 0
Non-Domain-only Rules Excluded: 5890
Domain-only Rules Excluded (unsupported options): 107
Domain-only Rules Excluded (exception conflict): 22
Domain-only Rules Output: 3135
```

&nbsp;

## Hagezi Blocklists Light (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |
| Pi-Hole | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)
- Title: HaGeZi's Light DNS Blocklist
- Version: 2024.0809.0005.31
- Last Modified: 09 Aug 2024 00:05 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 67860
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 67848
```

&nbsp;

## Hagezi Blocklists Normal (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |
| Pi-Hole | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)
- Title: HaGeZi's Normal DNS Blocklist
- Version: 2024.0809.0015.25
- Last Modified: 09 Aug 2024 00:15 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 143041
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 143029
```

&nbsp;

## Blackmatrix7's Advertising Rules (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [bm7.list](https://mili-tan.github.io/justdomains/lists/bm7.list) |
| Pi-Hole | [bm7.list](https://mili-tan.github.io/justdomains/lists/bm7.list) |

**Source:** [https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/Advertising/Advertising.txt](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/Advertising/Advertising.txt)

**Conversion Details:**
```
Total Lines Processed: 151779
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 209
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 151565
```

&nbsp;

## Blackmatrix7's Advertising Rules Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [bm7l.list](https://mili-tan.github.io/justdomains/lists/bm7l.list) |
| Pi-Hole | [bm7l.list](https://mili-tan.github.io/justdomains/lists/bm7l.list) |

**Source:** [https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingLite/AdvertisingLite.txt](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingLite/AdvertisingLite.txt)

**Conversion Details:**
```
Total Lines Processed: 37607
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37600
```

&nbsp;

## d3Host List by d3ward (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [d3.list](https://mili-tan.github.io/justdomains/lists/d3.list) |
| Pi-Hole | [d3.list](https://mili-tan.github.io/justdomains/lists/d3.list) |

**Source:** [https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.adblock](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.adblock)
- Title: d3Host List by d3ward
- Homepage: [https://github.com/d3ward/toolz](https://github.com/d3ward/toolz)

**Conversion Details:**
```
Total Lines Processed: 225
Comment Lines: 47
Empty Lines: 43
Non-Domain-only Rules Excluded: 47
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 131
```

&nbsp;

## NoCoin Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |
| Pi-Hole | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 12 April 2023
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 420
Comment Lines: 10
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 409
```

&nbsp;

## Hagezi Anti Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |
| Pi-Hole | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- Title: HaGeZi's Encrypted DNS/VPN/TOR/Proxy Bypass DNS Blocklist
- Version: 2024.0807.2211.43
- Last Modified: 07 Aug 2024 22:11 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 3085
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 3072
```

&nbsp;

## DDNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [ddns.list](https://mili-tan.github.io/justdomains/lists/ddns.list) |
| Pi-Hole | [ddns.list](https://mili-tan.github.io/justdomains/lists/ddns.list) |

**Source:** [https://mili.one/lists/ddns.txt](https://mili.one/lists/ddns.txt)

**Conversion Details:**
```
Total Lines Processed: 36046
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 4
Duplicate Hosts (Ignored): 585
Hosts Output: 35457
```

&nbsp;

## IPFS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [ipfs.list](https://mili-tan.github.io/justdomains/lists/ipfs.list) |
| Pi-Hole | [ipfs.list](https://mili-tan.github.io/justdomains/lists/ipfs.list) |

**Source:** [https://mili.one/lists/ipfs.txt](https://mili.one/lists/ipfs.txt)

**Conversion Details:**
```
Total Lines Processed: 78
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 77
```

&nbsp;

## Anti SafeSearch Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nosafesearch.list](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |
| Pi-Hole | [nosafesearch.list](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |

**Source:** [https://mili.one/lists/nosafesearch.txt](https://mili.one/lists/nosafesearch.txt)

**Conversion Details:**
```
Total Lines Processed: 234
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 234
```

&nbsp;

## NextDNS Native Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nativetracking.list](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |
| Pi-Hole | [nativetracking.list](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |

**Source:** [https://mili.one/lists/nativetracking.txt](https://mili.one/lists/nativetracking.txt)

**Conversion Details:**
```
Total Lines Processed: 98
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 1
Hosts Output: 97
```

&nbsp;

## Blackmatrix7's MiTV Rules (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [bm7mitv.list](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |
| Pi-Hole | [bm7mitv.list](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |

**Source:** [https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingMiTV/AdvertisingMiTV.txt](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingMiTV/AdvertisingMiTV.txt)

**Conversion Details:**
```
Total Lines Processed: 172
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 165
```

&nbsp;

## Anti HTTPDNS Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [httpdns.list](https://mili-tan.github.io/justdomains/lists/httpdns.list) |
| Pi-Hole | [httpdns.list](https://mili-tan.github.io/justdomains/lists/httpdns.list) |

**Source:** [https://mili.one/lists/httpdns.txt](https://mili.one/lists/httpdns.txt)

**Conversion Details:**
```
Total Lines Processed: 24
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 24
```

&nbsp;

## Anti Cellular Identity (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cellular-identity.list](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |
| Pi-Hole | [cellular-identity.list](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |

**Source:** [https://mili.one/lists/cellular-identity.txt](https://mili.one/lists/cellular-identity.txt)

**Conversion Details:**
```
Total Lines Processed: 6
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 6
```

&nbsp;

# License:
Each converted / modified list file is licensed under the same license as the original list.

For more details, see the [LICENSES](LICENSES) file.

&nbsp;

# Reporting Conversion Issues:
If you find an issue in the output of the conversion process (i.e. comparing to the original upstream list), please report it over on: https://github.com/justdomains/ci/issues

**NOTE: We do not manage the upstream lists themselves, and will not be able to add any new blocks to the lists.**

&nbsp;

<sup>These files are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, arising from, out of or in connection with the files or the use of the files.</sup>

<sub>Any and all trademarks are the property of their respective owners.</sub>
