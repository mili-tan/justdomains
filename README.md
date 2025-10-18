# DOMAIN-ONLY Filter Lists
**Last Updated:** 2025-10-18 16:15:17

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
  - [AWAvenue Ads Rule](#awavenue-ads-rule-domains-only) (Domains-only)
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
  - [Energized Spark](#energized-spark-domains-only) (Domains-only)
  - [Energized Blu](#energized-blu-domains-only) (Domains-only)
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
| [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) | MIT | 80101 | [**Download**](https://mili-tan.github.io/justdomains/lists/stevenblack.list) | 17 October 2025 03:02:46 (UTC) |
| [Yoyos Hosts](#yoyos-hosts-domains-only) | MCRAE GENERAL PUBLIC LICENSE | 3439 | [**Download**](https://mili-tan.github.io/justdomains/lists/yoyo.list) |   Fri, 17 Oct 2025 08:38:46 GMT |
| [AdRules DNS List](#adrules-dns-list-domains-only) | WTFPL | 148009 | [**Download**](https://mili-tan.github.io/justdomains/lists/adrules.list) |  |
| [AdGuard DNS Filter](#adguard-dns-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 140703 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2025-10-18T14:05:29.206Z |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 43918 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 18 Oct 2025 15:57 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 45635 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 18 Oct 2025 15:57 UTC |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 153 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2025/10/08 15:00 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](https://easylist.to/pages/licence.html) | 852 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 18 Oct 2025 16:09 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 4902 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 18 Oct 2025 15:51 UTC |
| [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 72639 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AWAvenue Ads Rule](#awavenue-ads-rule-domains-only) | CC BY-NC-SA 4.0 | 855 | [**Download**](https://mili-tan.github.io/justdomains/lists/awavenue.list) |  |
| [OISD Small](#oisd-small-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 46798 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) | 2025-10-15T23:20:19+0000 |
| [OISD Big](#oisd-big-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 198855 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdbig.list) | 2025-10-15T23:20:05+0000 |
| [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 40997 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi.list) | 18 Oct 2025 11:17 UTC |
| [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 125054 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) | 18 Oct 2025 11:13 UTC |
| [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) | GPL2 | 229545 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7.list) |  |
| [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) | GPL2 | 37695 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7l.list) |  |
| [1Hosts Lite](#1hosts-lite-domains-only) | MPL-2.0 | 57836 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hl.list) | 2025-07-04T07:43:09.050Z |
| [1Hosts Pro](#1hosts-pro-domains-only) | MPL-2.0 | 146010 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hp.list) | 2025-07-04T07:43:04.073Z |
| [NoCoin Filter](#nocoin-filter-domains-only) | [MIT](https://mit-license.org/) | 313 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 05 March 2025 |
| [Prigent Crypto](#prigent-crypto-domains-only) | CC BY-SA 4.0 | 16291 | [**Download**](https://mili-tan.github.io/justdomains/lists/coinblocker.list) |  |
| [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 6152 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) | 18 Oct 2025 11:43 UTC |
| [DDNS Filter](#ddns-filter-domains-only) | Unlicense | 33785 | [**Download**](https://mili-tan.github.io/justdomains/lists/ddns.list) |  |
| [IPFS Filter](#ipfs-filter-domains-only) | MIT | 77 | [**Download**](https://mili-tan.github.io/justdomains/lists/ipfs.list) |  |
| [Search Filter](#search-filter-domains-only) | MIT | 175 | [**Download**](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |  |
| [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) | MIT | 98 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |  |
| [Hagezi Mobile Native Tracking Filter](#hagezi-mobile-native-tracking-filter-domains-only) | GPL3 | 1332 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativemobile.list) |  |
| [Hagezi Software Native Tracking Filter](#hagezi-software-native-tracking-filter-domains-only) | GPL3 | 1020 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativesoft.list) |  |
| [Hagezi TV Native Tracking Filter](#hagezi-tv-native-tracking-filter-domains-only) | GPL3 | 92 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetv.list) |  |
| [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) | GPL2 | 165 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |  |
| [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) | GPL3 | 21 | [**Download**](https://mili-tan.github.io/justdomains/lists/httpdns.list) |  |
| [HideMyTel](#hidemytel-domains-only) | MIT | 23 | [**Download**](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |  |
| [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) | MIT | 66 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |  |
| [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) | MIT | 13 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |  |
| [Anti-AD PCDN](#anti-ad-pcdn-domains-only) | MIT | 30 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |  |
| [KAD](#kad-domains-only) | CC BY-SA 4.0 | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/kad.list) | Sat, 18 Oct 2025, 17:59 UTC+02:00 |
| [Energized Spark](#energized-spark-domains-only) | MIT | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/e-spark.list) |  |
| [Energized Blu](#energized-blu-domains-only) | MIT | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/e-blu.list) |  |

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
- Last Modified: 17 October 2025 03:02:46 (UTC)

**Conversion Details:**
```
Total Lines Processed: 86850
Comment Lines: 4234
Empty Lines: 2501
Invalid Lines: 0
Non-Loopback Lines (Ignored): 7
Local Hosts (Ignored): 5
Invalid Hosts (Ignored): 2
Duplicate Hosts (Ignored): 0
Hosts Output: 80101
```

&nbsp;

## Yoyos Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |
| Pi-Hole | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |

**Source:** [https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)
- Last Modified:   Fri, 17 Oct 2025 08:38:46 GMT

**Conversion Details:**
```
Total Lines Processed: 3453
Comment Lines: 14
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 3439
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
Total Lines Processed: 148415
Comment Lines: 7
Empty Lines: 0
Non-Domain-only Rules Excluded: 399
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 148009
```

&nbsp;

## AdGuard DNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.97.59
- Last Modified: 2025-10-18T14:05:29.206Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 143156
Comment Lines: 1536
Empty Lines: 0
Non-Domain-only Rules Excluded: 843
Domain-only Rules Excluded (unsupported options): 4
Domain-only Rules Excluded (exception conflict): 70
Domain-only Rules Output: 140703
```

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202510181557
- Last Modified: 18 Oct 2025 15:57 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 76602
Comment Lines: 272
Empty Lines: 0
Non-Domain-only Rules Excluded: 27892
Domain-only Rules Excluded (unsupported options): 4451
Domain-only Rules Excluded (exception conflict): 69
Domain-only Rules Output: 43918
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202510181557
- Last Modified: 18 Oct 2025 15:57 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 55112
Comment Lines: 731
Empty Lines: 1
Non-Domain-only Rules Excluded: 8351
Domain-only Rules Excluded (unsupported options): 211
Domain-only Rules Excluded (exception conflict): 184
Domain-only Rules Output: 45635
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202510081500
- Last Modified: 2025/10/08 15:00 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1855
Comment Lines: 20
Empty Lines: 0
Non-Domain-only Rules Excluded: 1673
Domain-only Rules Excluded (unsupported options): 8
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 153
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202510181609
- Last Modified: 18 Oct 2025 16:09 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 48915
Comment Lines: 1349
Empty Lines: 0
Non-Domain-only Rules Excluded: 46599
Domain-only Rules Excluded (unsupported options): 70
Domain-only Rules Excluded (exception conflict): 45
Domain-only Rules Output: 852
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202510181551
- Last Modified: 18 Oct 2025 15:51 UTC
- Homepage: [https://github.com/easylist/easylistchina/](https://github.com/easylist/easylistchina/)

**Conversion Details:**
```
Total Lines Processed: 18297
Comment Lines: 104
Empty Lines: 0
Non-Domain-only Rules Excluded: 13126
Domain-only Rules Excluded (unsupported options): 154
Domain-only Rules Excluded (exception conflict): 11
Domain-only Rules Output: 4902
```

&nbsp;

## AdGuard Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.93.8
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 124450
Comment Lines: 3567
Empty Lines: 0
Non-Domain-only Rules Excluded: 43860
Domain-only Rules Excluded (unsupported options): 594
Domain-only Rules Excluded (exception conflict): 3790
Domain-only Rules Output: 72639
```

&nbsp;

## AWAvenue Ads Rule (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |
| Pi-Hole | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |

**Source:** [https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- Title: AWAvenue Ads Rule
- Version: 1.6.8-release

**Conversion Details:**
```
Total Lines Processed: 871
Comment Lines: 8
Empty Lines: 3
Non-Domain-only Rules Excluded: 8
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 855
```

&nbsp;

## OISD Small (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |
| Pi-Hole | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |

**Source:** [https://small.oisd.nl](https://small.oisd.nl)
- Title: oisd small
- Version: 202510152320
- Last Modified: 2025-10-15T23:20:19+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 46810
Comment Lines: 10
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 46798
```

&nbsp;

## OISD Big (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |
| Pi-Hole | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |

**Source:** [https://big.oisd.nl](https://big.oisd.nl)
- Title: oisd big
- Version: 202510152320
- Last Modified: 2025-10-15T23:20:05+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 198867
Comment Lines: 10
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 198855
```

&nbsp;

## Hagezi Blocklists Light (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |
| Pi-Hole | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)
- Title: HaGeZi's Light DNS Blocklist
- Version: 2025.1018.1117.40
- Last Modified: 18 Oct 2025 11:17 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 41010
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 40997
```

&nbsp;

## Hagezi Blocklists Normal (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |
| Pi-Hole | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)
- Title: HaGeZi's Normal DNS Blocklist
- Version: 2025.1018.1113.04
- Last Modified: 18 Oct 2025 11:13 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 125067
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 125054
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
Total Lines Processed: 229759
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 209
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 229545
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
Total Lines Processed: 37702
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37695
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
- Version: 2025.1018.1143.33
- Last Modified: 18 Oct 2025 11:43 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 6166
Comment Lines: 13
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 6152
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
Total Lines Processed: 33787
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 2
Duplicate Hosts (Ignored): 0
Hosts Output: 33785
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
Total Lines Processed: 1332
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 1332
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
Total Lines Processed: 1020
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 1020
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
Total Lines Processed: 66
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 66
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
Total Lines Processed: 30
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 30
```

&nbsp;

## KAD (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [kad.list](https://mili-tan.github.io/justdomains/lists/kad.list) |
| Pi-Hole | [kad.list](https://mili-tan.github.io/justdomains/lists/kad.list) |

**Source:** [https://raw.githubusercontent.com/FiltersHeroes/KAD/master/KAD.txt](https://raw.githubusercontent.com/FiltersHeroes/KAD/master/KAD.txt)
- Title: 馃嚨馃嚤 KAD - Przekr臋ty
- Version: 2025.10.18.2
- Last Modified: Sat, 18 Oct 2025, 17:59 UTC+02:00
- Homepage: [https://kadantiscam.netlify.app](https://kadantiscam.netlify.app)

**Conversion Details:**
```
Total Lines Processed: 31110
Comment Lines: 43
Empty Lines: 0
Non-Domain-only Rules Excluded: 392
Domain-only Rules Excluded (unsupported options): 30675
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 0
```

&nbsp;

## Energized Spark (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [e-spark.list](https://mili-tan.github.io/justdomains/lists/e-spark.list) |
| Pi-Hole | [e-spark.list](https://mili-tan.github.io/justdomains/lists/e-spark.list) |

**Source:** [https://energized.pro/spark/adblock.txt](https://energized.pro/spark/adblock.txt)

**Conversion Details:**
```
Total Lines Processed: 22
Comment Lines: 0
Empty Lines: 0
Non-Domain-only Rules Excluded: 22
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 0
```

&nbsp;

## Energized Blu (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [e-blu.list](https://mili-tan.github.io/justdomains/lists/e-blu.list) |
| Pi-Hole | [e-blu.list](https://mili-tan.github.io/justdomains/lists/e-blu.list) |

**Source:** [https://energized.pro/blu/adblock.txt](https://energized.pro/blu/adblock.txt)

**Conversion Details:**
```
Total Lines Processed: 22
Comment Lines: 0
Empty Lines: 0
Non-Domain-only Rules Excluded: 22
Domain-only Rules Excluded (unsupported options): 0
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
