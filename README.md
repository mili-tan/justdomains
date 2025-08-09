# DOMAIN-ONLY Filter Lists
**Last Updated:** 2025-08-09 16:17:25

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
  - [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) (Domains-only)
  - [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) (Domains-only)
  - [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) (Domains-only)
  - [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) (Domains-only)
  - [1Hosts Lite](#1hosts-lite-domains-only) (Domains-only)
  - [1Hosts Pro](#1hosts-pro-domains-only) (Domains-only)
  - [NoCoin Filter](#nocoin-filter-domains-only) (Domains-only)
  - [Prigent Crypto](#prigent-crypto-domains-only) (Domains-only)
  - [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) (Domains-only)
  - [DDNS Filter](#ddns-filter-domains-only) (Domains-only)
  - [IPFS Filter](#ipfs-filter-domains-only) (Domains-only)
  - [Search Filter](#search-filter-domains-only) (Domains-only)
  - [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) (Domains-only)
  - [Hagezi Mobile Native Tracking Filter](#hagezi-mobile-native-tracking-filter-domains-only) (Domains-only)
  - [Hagezi Software Native Tracking Filter](#hagezi-software-native-tracking-filter-domains-only) (Domains-only)
  - [Hagezi TV Native Tracking Filter](#hagezi-tv-native-tracking-filter-domains-only) (Domains-only)
  - [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) (Domains-only)
  - [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) (Domains-only)
  - [HideMyTel](#hidemytel-domains-only) (Domains-only)
  - [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) (Domains-only)
  - [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) (Domains-only)
  - [Anti-AD PCDN](#anti-ad-pcdn-domains-only) (Domains-only)
  - [KAD](#kad-domains-only) (Domains-only)
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
| [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) | MIT | 229083 | [**Download**](https://mili-tan.github.io/justdomains/lists/stevenblack.list) | 08 August 2025 14:39:21 (UTC) |
| [Yoyos Hosts](#yoyos-hosts-domains-only) | MCRAE GENERAL PUBLIC LICENSE | 3419 | [**Download**](https://mili-tan.github.io/justdomains/lists/yoyo.list) |   Tue, 05 Aug 2025 15:17:49 GMT |
| [AdRules DNS List](#adrules-dns-list-domains-only) | WTFPL | 130678 | [**Download**](https://mili-tan.github.io/justdomains/lists/adrules.list) |  |
| [AdGuard DNS Filter](#adguard-dns-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 125632 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2025-08-09T14:05:55.696Z |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 38306 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 09 Aug 2025 15:50 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 45505 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 09 Aug 2025 15:50 UTC |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 152 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2025/07/28 20:35 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](https://easylist.to/pages/licence.html) | 847 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 09 Aug 2025 15:50 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 5062 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 09 Aug 2025 16:02 UTC |
| [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 66800 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AWAvenue Adblock Rule](#awavenue-adblock-rule-domains-only) | CC BY-NC-SA 4.0 | 849 | [**Download**](https://mili-tan.github.io/justdomains/lists/awavenue.list) |  |
| [OISD Small](#oisd-small-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 44435 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) | 2025-08-09T04:19:53+0000 |
| [OISD Big](#oisd-big-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 201495 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdbig.list) | 2025-08-09T14:47:15+0000 |
| [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 57177 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi.list) | 09 Aug 2025 11:29 UTC |
| [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 135102 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) | 09 Aug 2025 11:24 UTC |
| [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) | GPL2 | 209769 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7.list) |  |
| [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) | GPL2 | 37689 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7l.list) |  |
| [1Hosts Lite](#1hosts-lite-domains-only) | MPL-2.0 | 57836 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hl.list) | 2025-07-04T07:43:09.050Z |
| [1Hosts Pro](#1hosts-pro-domains-only) | MPL-2.0 | 146010 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hp.list) | 2025-07-04T07:43:04.073Z |
| [NoCoin Filter](#nocoin-filter-domains-only) | [MIT](https://mit-license.org/) | 313 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 05 March 2025 |
| [Prigent Crypto](#prigent-crypto-domains-only) | CC BY-SA 4.0 | 16291 | [**Download**](https://mili-tan.github.io/justdomains/lists/coinblocker.list) |  |
| [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 5340 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) | 09 Aug 2025 12:11 UTC |
| [DDNS Filter](#ddns-filter-domains-only) | Unlicense | 32414 | [**Download**](https://mili-tan.github.io/justdomains/lists/ddns.list) |  |
| [IPFS Filter](#ipfs-filter-domains-only) | MIT | 77 | [**Download**](https://mili-tan.github.io/justdomains/lists/ipfs.list) |  |
| [Search Filter](#search-filter-domains-only) | MIT | 175 | [**Download**](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |  |
| [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) | MIT | 98 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |  |
| [Hagezi Mobile Native Tracking Filter](#hagezi-mobile-native-tracking-filter-domains-only) | GPL3 | 1371 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativemobile.list) |  |
| [Hagezi Software Native Tracking Filter](#hagezi-software-native-tracking-filter-domains-only) | GPL3 | 1071 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativesoft.list) |  |
| [Hagezi TV Native Tracking Filter](#hagezi-tv-native-tracking-filter-domains-only) | GPL3 | 92 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetv.list) |  |
| [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) | GPL2 | 165 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |  |
| [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) | GPL3 | 21 | [**Download**](https://mili-tan.github.io/justdomains/lists/httpdns.list) |  |
| [HideMyTel](#hidemytel-domains-only) | MIT | 23 | [**Download**](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |  |
| [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) | MIT | 64 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |  |
| [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) | MIT | 13 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |  |
| [Anti-AD PCDN](#anti-ad-pcdn-domains-only) | MIT | 28 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |  |
| [KAD](#kad-domains-only) | CC BY-SA 4.0 | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/kad.list) | Sat, 09 Aug 2025, 14:45 UTC+02:00 |

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
- Last Modified: 08 August 2025 14:39:21 (UTC)

**Conversion Details:**
```
Total Lines Processed: 235814
Comment Lines: 4226
Empty Lines: 2493
Invalid Lines: 0
Non-Loopback Lines (Ignored): 7
Local Hosts (Ignored): 4
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 229083
```

&nbsp;

## Yoyos Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |
| Pi-Hole | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |

**Source:** [https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)
- Last Modified:   Tue, 05 Aug 2025 15:17:49 GMT

**Conversion Details:**
```
Total Lines Processed: 3433
Comment Lines: 14
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 3419
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
Total Lines Processed: 131071
Comment Lines: 7
Empty Lines: 0
Non-Domain-only Rules Excluded: 386
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 130678
```

&nbsp;

## AdGuard DNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.89.29
- Last Modified: 2025-08-09T14:05:55.696Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 128042
Comment Lines: 1516
Empty Lines: 0
Non-Domain-only Rules Excluded: 821
Domain-only Rules Excluded (unsupported options): 4
Domain-only Rules Excluded (exception conflict): 69
Domain-only Rules Output: 125632
```

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202508091550
- Last Modified: 09 Aug 2025 15:50 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 71071
Comment Lines: 295
Empty Lines: 0
Non-Domain-only Rules Excluded: 27977
Domain-only Rules Excluded (unsupported options): 4422
Domain-only Rules Excluded (exception conflict): 71
Domain-only Rules Output: 38306
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202508091550
- Last Modified: 09 Aug 2025 15:50 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 54761
Comment Lines: 717
Empty Lines: 1
Non-Domain-only Rules Excluded: 8143
Domain-only Rules Excluded (unsupported options): 210
Domain-only Rules Excluded (exception conflict): 186
Domain-only Rules Output: 45505
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202507282035
- Last Modified: 2025/07/28 20:35 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1850
Comment Lines: 20
Empty Lines: 0
Non-Domain-only Rules Excluded: 1669
Domain-only Rules Excluded (unsupported options): 8
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 152
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202508091550
- Last Modified: 09 Aug 2025 15:50 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 48594
Comment Lines: 1347
Empty Lines: 0
Non-Domain-only Rules Excluded: 46288
Domain-only Rules Excluded (unsupported options): 70
Domain-only Rules Excluded (exception conflict): 42
Domain-only Rules Output: 847
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202508091602
- Last Modified: 09 Aug 2025 16:02 UTC
- Homepage: [https://github.com/easylist/easylistchina/](https://github.com/easylist/easylistchina/)

**Conversion Details:**
```
Total Lines Processed: 18437
Comment Lines: 104
Empty Lines: 0
Non-Domain-only Rules Excluded: 13106
Domain-only Rules Excluded (unsupported options): 154
Domain-only Rules Excluded (exception conflict): 11
Domain-only Rules Output: 5062
```

&nbsp;

## AdGuard Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.89.32
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 113616
Comment Lines: 3460
Empty Lines: 0
Non-Domain-only Rules Excluded: 42518
Domain-only Rules Excluded (unsupported options): 557
Domain-only Rules Excluded (exception conflict): 281
Domain-only Rules Output: 66800
```

&nbsp;

## AWAvenue Adblock Rule (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |
| Pi-Hole | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |

**Source:** [https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- Title: AWAvenue Ads Rule
- Version: 1.6.8-release

**Conversion Details:**
```
Total Lines Processed: 865
Comment Lines: 8
Empty Lines: 3
Non-Domain-only Rules Excluded: 8
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 849
```

&nbsp;

## OISD Small (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |
| Pi-Hole | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |

**Source:** [https://small.oisd.nl](https://small.oisd.nl)
- Title: oisd small
- Version: 202508090419
- Last Modified: 2025-08-09T04:19:53+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 44447
Comment Lines: 10
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 44435
```

&nbsp;

## OISD Big (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |
| Pi-Hole | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |

**Source:** [https://big.oisd.nl](https://big.oisd.nl)
- Title: oisd big
- Version: 202508091447
- Last Modified: 2025-08-09T14:47:15+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 201507
Comment Lines: 10
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 201495
```

&nbsp;

## Hagezi Blocklists Light (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |
| Pi-Hole | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)
- Title: HaGeZi's Light DNS Blocklist
- Version: 2025.0809.1129.28
- Last Modified: 09 Aug 2025 11:29 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 57189
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 57177
```

&nbsp;

## Hagezi Blocklists Normal (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |
| Pi-Hole | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)
- Title: HaGeZi's Normal DNS Blocklist
- Version: 2025.0809.1124.02
- Last Modified: 09 Aug 2025 11:24 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 135114
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 135102
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
Total Lines Processed: 209983
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 209
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 209769
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
Total Lines Processed: 37696
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37689
```

&nbsp;

## 1Hosts Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [1hl.list](https://mili-tan.github.io/justdomains/lists/1hl.list) |
| Pi-Hole | [1hl.list](https://mili-tan.github.io/justdomains/lists/1hl.list) |

**Source:** [https://o0.pages.dev/Lite/adblock.txt](https://o0.pages.dev/Lite/adblock.txt)
- Title: 1Hosts (Lite)
- Last Modified: 2025-07-04T07:43:09.050Z
- Homepage: [https://github.com/badmojr/1Hosts](https://github.com/badmojr/1Hosts)

**Conversion Details:**
```
Total Lines Processed: 57852
Comment Lines: 15
Empty Lines: 1
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 57836
```

&nbsp;

## 1Hosts Pro (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [1hp.list](https://mili-tan.github.io/justdomains/lists/1hp.list) |
| Pi-Hole | [1hp.list](https://mili-tan.github.io/justdomains/lists/1hp.list) |

**Source:** [https://o0.pages.dev/Pro/adblock.txt](https://o0.pages.dev/Pro/adblock.txt)
- Title: 1Hosts (Pro)
- Last Modified: 2025-07-04T07:43:04.073Z
- Homepage: [https://github.com/badmojr/1Hosts](https://github.com/badmojr/1Hosts)

**Conversion Details:**
```
Total Lines Processed: 146027
Comment Lines: 15
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 146010
```

&nbsp;

## NoCoin Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |
| Pi-Hole | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 05 March 2025
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 324
Comment Lines: 10
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 313
```

&nbsp;

## Prigent Crypto (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [coinblocker.list](https://mili-tan.github.io/justdomains/lists/coinblocker.list) |
| Pi-Hole | [coinblocker.list](https://mili-tan.github.io/justdomains/lists/coinblocker.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/v.firebog.net/hosts/Prigent-Crypto.txt](https://dns-mili-tan.koyeb.app/tohosts/v.firebog.net/hosts/Prigent-Crypto.txt)

**Conversion Details:**
```
Total Lines Processed: 16291
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 16291
```

&nbsp;

## Hagezi Anti Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |
| Pi-Hole | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- Title: HaGeZi's Encrypted DNS/VPN/TOR/Proxy Bypass DNS Blocklist
- Version: 2025.0809.1211.14
- Last Modified: 09 Aug 2025 12:11 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 5353
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 5340
```

&nbsp;

## DDNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [ddns.list](https://mili-tan.github.io/justdomains/lists/ddns.list) |
| Pi-Hole | [ddns.list](https://mili-tan.github.io/justdomains/lists/ddns.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/alexandrosmagos/dyn-dns-list/refs/heads/master/links.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/alexandrosmagos/dyn-dns-list/refs/heads/master/links.txt)

**Conversion Details:**
```
Total Lines Processed: 32416
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 2
Duplicate Hosts (Ignored): 0
Hosts Output: 32414
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

## Search Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nosafesearch.list](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |
| Pi-Hole | [nosafesearch.list](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/nextdns/no-safesearch/refs/heads/main/domains](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/nextdns/no-safesearch/refs/heads/main/domains)

**Conversion Details:**
```
Total Lines Processed: 175
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 175
```

&nbsp;

## NextDNS Native Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nativetracking.list](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |
| Pi-Hole | [nativetracking.list](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |

**Source:** [https://dns-mili-tan.koyeb.app/filestohosts/alexa,apple,huawei,roku,samsung,sonos,windows,xiaomi/raw.githubusercontent.com/nextdns/native-tracking-domains/refs/heads/main/domains](https://dns-mili-tan.koyeb.app/filestohosts/alexa,apple,huawei,roku,samsung,sonos,windows,xiaomi/raw.githubusercontent.com/nextdns/native-tracking-domains/refs/heads/main/domains)

**Conversion Details:**
```
Total Lines Processed: 99
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 1
Hosts Output: 98
```

&nbsp;

## Hagezi Mobile Native Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nativemobile.list](https://mili-tan.github.io/justdomains/lists/nativemobile.list) |
| Pi-Hole | [nativemobile.list](https://mili-tan.github.io/justdomains/lists/nativemobile.list) |

**Source:** [https://dns-mili-tan.koyeb.app/filestohosts/native.apple-onlydomains.txt,native.huawei-onlydomains.txt,native.samsung.txt,native.vivo-onlydomains.txt,native.oppo-realme-onlydomains.txt,native.xiaomi-onlydomains.txt/raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard](https://dns-mili-tan.koyeb.app/filestohosts/native.apple-onlydomains.txt,native.huawei-onlydomains.txt,native.samsung.txt,native.vivo-onlydomains.txt,native.oppo-realme-onlydomains.txt,native.xiaomi-onlydomains.txt/raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard)

**Conversion Details:**
```
Total Lines Processed: 1371
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 1371
```

&nbsp;

## Hagezi Software Native Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nativesoft.list](https://mili-tan.github.io/justdomains/lists/nativesoft.list) |
| Pi-Hole | [nativesoft.list](https://mili-tan.github.io/justdomains/lists/nativesoft.list) |

**Source:** [https://dns-mili-tan.koyeb.app/filestohosts/native.winoffice-onlydomains.txt,native.amazon-onlydomains.txt,native.tiktok-onlydomains.txt/raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard](https://dns-mili-tan.koyeb.app/filestohosts/native.winoffice-onlydomains.txt,native.amazon-onlydomains.txt,native.tiktok-onlydomains.txt/raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard)

**Conversion Details:**
```
Total Lines Processed: 1071
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 1071
```

&nbsp;

## Hagezi TV Native Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nativetv.list](https://mili-tan.github.io/justdomains/lists/nativetv.list) |
| Pi-Hole | [nativetv.list](https://mili-tan.github.io/justdomains/lists/nativetv.list) |

**Source:** [https://dns-mili-tan.koyeb.app/filestohosts/native.lgwebos.txt,native.roku.txt/raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard](https://dns-mili-tan.koyeb.app/filestohosts/native.lgwebos.txt,native.roku.txt/raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard)

**Conversion Details:**
```
Total Lines Processed: 92
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 92
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

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/VirgilClyne/GetSomeFries/main/ruleset/HTTPDNS.Block.list](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/VirgilClyne/GetSomeFries/main/ruleset/HTTPDNS.Block.list)

**Conversion Details:**
```
Total Lines Processed: 21
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 21
```

&nbsp;

## HideMyTel (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cellular-identity.list](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |
| Pi-Hole | [cellular-identity.list](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |

**Source:** [https://raw.githubusercontent.com/notSachiho/HideMyTel/refs/heads/main/hosts](https://raw.githubusercontent.com/notSachiho/HideMyTel/refs/heads/main/hosts)

**Conversion Details:**
```
Total Lines Processed: 25
Comment Lines: 1
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 23
```

&nbsp;

## Anti-AD Encrypted DNS (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [anti-ad-dns.list](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |
| Pi-Hole | [anti-ad-dns.list](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/dns.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/dns.txt)

**Conversion Details:**
```
Total Lines Processed: 64
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 64
```

&nbsp;

## Anti-AD Auto Number Verification (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [anti-ad-anv.list](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |
| Pi-Hole | [anti-ad-anv.list](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/anv.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/anv.txt)

**Conversion Details:**
```
Total Lines Processed: 13
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 13
```

&nbsp;

## Anti-AD PCDN (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [anti-ad-pcdn.list](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |
| Pi-Hole | [anti-ad-pcdn.list](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/pcdn.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/pcdn.txt)

**Conversion Details:**
```
Total Lines Processed: 28
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 28
```

&nbsp;

## KAD (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [kad.list](https://mili-tan.github.io/justdomains/lists/kad.list) |
| Pi-Hole | [kad.list](https://mili-tan.github.io/justdomains/lists/kad.list) |

**Source:** [https://raw.githubusercontent.com/FiltersHeroes/KAD/master/KAD.txt](https://raw.githubusercontent.com/FiltersHeroes/KAD/master/KAD.txt)
- Title: 馃嚨馃嚤 KAD - Przekr臋ty
- Version: 2025.8.9.1
- Last Modified: Sat, 09 Aug 2025, 14:45 UTC+02:00
- Homepage: [https://kadantiscam.netlify.app](https://kadantiscam.netlify.app)

**Conversion Details:**
```
Total Lines Processed: 110413
Comment Lines: 43
Empty Lines: 0
Non-Domain-only Rules Excluded: 383
Domain-only Rules Excluded (unsupported options): 109987
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 0
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
