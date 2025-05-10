# DOMAIN-ONLY Filter Lists
**Last Updated:** 2025-05-10 16:15:30

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
  - [CERT.PL's Warning List](#certpls-warning-list-domains-only) (Domains-only)
  - [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) (Domains-only)
  - [DDNS Filter](#ddns-filter-domains-only) (Domains-only)
  - [IPFS Filter](#ipfs-filter-domains-only) (Domains-only)
  - [Search Filter](#search-filter-domains-only) (Domains-only)
  - [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) (Domains-only)
  - [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) (Domains-only)
  - [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) (Domains-only)
  - [HideMyTel](#hidemytel-domains-only) (Domains-only)
  - [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) (Domains-only)
  - [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) (Domains-only)
  - [Anti-AD PCDN](#anti-ad-pcdn-domains-only) (Domains-only)
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
| [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) | MIT | 165874 | [**Download**](https://mili-tan.github.io/justdomains/lists/stevenblack.list) | 08 May 2025 20:15:09 (UTC) |
| [Yoyos Hosts](#yoyos-hosts-domains-only) | MCRAE GENERAL PUBLIC LICENSE | 3438 | [**Download**](https://mili-tan.github.io/justdomains/lists/yoyo.list) |   Thu, 01 May 2025 11:16:00 GMT |
| [AdRules DNS List](#adrules-dns-list-domains-only) | WTFPL | 115930 | [**Download**](https://mili-tan.github.io/justdomains/lists/adrules.list) |  |
| [AdGuard DNS Filter](#adguard-dns-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 105411 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2025-05-10T12:01:40.386Z |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 29188 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 10 May 2025 14:55 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 45914 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 10 May 2025 14:55 UTC |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 150 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2025/05/03 07:31 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](https://easylist.to/pages/licence.html) | 822 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 10 May 2025 14:55 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 4289 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 10 May 2025 16:01 UTC |
| [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 55675 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AWAvenue Adblock Rule](#awavenue-adblock-rule-domains-only) | CC BY-NC-SA 4.0 | 777 | [**Download**](https://mili-tan.github.io/justdomains/lists/awavenue.list) |  |
| [OISD Small](#oisd-small-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 44481 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) | 2025-05-10T15:09:43+0000 |
| [OISD Big](#oisd-big-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 179586 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdbig.list) | 2025-05-10T15:09:29+0000 |
| [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 41506 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi.list) | 10 May 2025 12:22 UTC |
| [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 107565 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) | 10 May 2025 12:13 UTC |
| [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) | GPL2 | 180439 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7.list) |  |
| [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) | GPL2 | 37670 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7l.list) |  |
| [1Hosts Lite](#1hosts-lite-domains-only) | MPL-2.0 | 55792 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hl.list) | 2025-05-10T07:37:47.176Z |
| [1Hosts Pro](#1hosts-pro-domains-only) | MPL-2.0 | 146185 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hp.list) | 2025-05-10T07:37:44.191Z |
| [NoCoin Filter](#nocoin-filter-domains-only) | [MIT](https://mit-license.org/) | 313 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 05 March 2025 |
| [CERT.PL's Warning List](#certpls-warning-list-domains-only) | AGPL3 | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/certpl.list) |  |
| [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 4058 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) | 10 May 2025 14:00 UTC |
| [DDNS Filter](#ddns-filter-domains-only) | Unlicense | 32414 | [**Download**](https://mili-tan.github.io/justdomains/lists/ddns.list) |  |
| [IPFS Filter](#ipfs-filter-domains-only) | MIT | 77 | [**Download**](https://mili-tan.github.io/justdomains/lists/ipfs.list) |  |
| [Search Filter](#search-filter-domains-only) | MIT | 175 | [**Download**](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |  |
| [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) | MIT | 98 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |  |
| [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) | GPL2 | 165 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |  |
| [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) | GPL3 | 21 | [**Download**](https://mili-tan.github.io/justdomains/lists/httpdns.list) |  |
| [HideMyTel](#hidemytel-domains-only) | MIT | 23 | [**Download**](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |  |
| [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) | MIT | 64 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |  |
| [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) | MIT | 13 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |  |
| [Anti-AD PCDN](#anti-ad-pcdn-domains-only) | MIT | 28 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |  |

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
- Last Modified: 08 May 2025 20:15:09 (UTC)

**Conversion Details:**
```
Total Lines Processed: 172601
Comment Lines: 4225
Empty Lines: 2490
Invalid Lines: 0
Non-Loopback Lines (Ignored): 7
Local Hosts (Ignored): 4
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 165874
```

&nbsp;

## Yoyos Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |
| Pi-Hole | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |

**Source:** [https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)
- Last Modified:   Thu, 01 May 2025 11:16:00 GMT

**Conversion Details:**
```
Total Lines Processed: 3452
Comment Lines: 14
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 3438
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
Total Lines Processed: 116308
Comment Lines: 7
Empty Lines: 0
Non-Domain-only Rules Excluded: 371
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 115930
```

&nbsp;

## AdGuard DNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.80.4
- Last Modified: 2025-05-10T12:01:40.386Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 107745
Comment Lines: 1467
Empty Lines: 0
Non-Domain-only Rules Excluded: 795
Domain-only Rules Excluded (unsupported options): 4
Domain-only Rules Excluded (exception conflict): 68
Domain-only Rules Output: 105411
```

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202505101455
- Last Modified: 10 May 2025 14:55 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 61990
Comment Lines: 288
Empty Lines: 0
Non-Domain-only Rules Excluded: 27699
Domain-only Rules Excluded (unsupported options): 4746
Domain-only Rules Excluded (exception conflict): 69
Domain-only Rules Output: 29188
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202505101455
- Last Modified: 10 May 2025 14:55 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 54970
Comment Lines: 708
Empty Lines: 1
Non-Domain-only Rules Excluded: 7956
Domain-only Rules Excluded (unsupported options): 209
Domain-only Rules Excluded (exception conflict): 183
Domain-only Rules Output: 45914
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202505030731
- Last Modified: 2025/05/03 07:31 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1844
Comment Lines: 20
Empty Lines: 0
Non-Domain-only Rules Excluded: 1665
Domain-only Rules Excluded (unsupported options): 8
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 150
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202505101455
- Last Modified: 10 May 2025 14:55 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 48259
Comment Lines: 1328
Empty Lines: 0
Non-Domain-only Rules Excluded: 45996
Domain-only Rules Excluded (unsupported options): 71
Domain-only Rules Excluded (exception conflict): 42
Domain-only Rules Output: 822
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202505101601
- Last Modified: 10 May 2025 16:01 UTC
- Homepage: [https://github.com/easylist/easylistchina/](https://github.com/easylist/easylistchina/)

**Conversion Details:**
```
Total Lines Processed: 17601
Comment Lines: 105
Empty Lines: 0
Non-Domain-only Rules Excluded: 13042
Domain-only Rules Excluded (unsupported options): 154
Domain-only Rules Excluded (exception conflict): 11
Domain-only Rules Output: 4289
```

&nbsp;

## AdGuard Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.84.67
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 166471
Comment Lines: 3341
Empty Lines: 0
Non-Domain-only Rules Excluded: 106684
Domain-only Rules Excluded (unsupported options): 480
Domain-only Rules Excluded (exception conflict): 291
Domain-only Rules Output: 55675
```

&nbsp;

## AWAvenue Adblock Rule (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |
| Pi-Hole | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |

**Source:** [https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- Title: AWAvenue Ads Rule
- Version: 1.6.5-release

**Conversion Details:**
```
Total Lines Processed: 808
Comment Lines: 8
Empty Lines: 3
Non-Domain-only Rules Excluded: 23
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 777
```

&nbsp;

## OISD Small (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |
| Pi-Hole | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |

**Source:** [https://small.oisd.nl](https://small.oisd.nl)
- Title: oisd small
- Version: 202505101509
- Last Modified: 2025-05-10T15:09:43+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 44494
Comment Lines: 11
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 44481
```

&nbsp;

## OISD Big (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |
| Pi-Hole | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |

**Source:** [https://big.oisd.nl](https://big.oisd.nl)
- Title: oisd big
- Version: 202505101509
- Last Modified: 2025-05-10T15:09:29+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 179599
Comment Lines: 11
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 179586
```

&nbsp;

## Hagezi Blocklists Light (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |
| Pi-Hole | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)
- Title: HaGeZi's Light DNS Blocklist
- Version: 2025.0510.1222.07
- Last Modified: 10 May 2025 12:22 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 41518
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 41506
```

&nbsp;

## Hagezi Blocklists Normal (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |
| Pi-Hole | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)
- Title: HaGeZi's Normal DNS Blocklist
- Version: 2025.0510.1213.05
- Last Modified: 10 May 2025 12:13 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 107577
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 107565
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
Total Lines Processed: 180653
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 209
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 180439
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
Total Lines Processed: 37677
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37670
```

&nbsp;

## 1Hosts Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [1hl.list](https://mili-tan.github.io/justdomains/lists/1hl.list) |
| Pi-Hole | [1hl.list](https://mili-tan.github.io/justdomains/lists/1hl.list) |

**Source:** [https://o0.pages.dev/Lite/adblock.txt](https://o0.pages.dev/Lite/adblock.txt)
- Title: 1Hosts (Lite)
- Last Modified: 2025-05-10T07:37:47.176Z

**Conversion Details:**
```
Total Lines Processed: 55808
Comment Lines: 15
Empty Lines: 1
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 55792
```

&nbsp;

## 1Hosts Pro (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [1hp.list](https://mili-tan.github.io/justdomains/lists/1hp.list) |
| Pi-Hole | [1hp.list](https://mili-tan.github.io/justdomains/lists/1hp.list) |

**Source:** [https://o0.pages.dev/Pro/adblock.txt](https://o0.pages.dev/Pro/adblock.txt)
- Title: 1Hosts (Pro)
- Last Modified: 2025-05-10T07:37:44.191Z

**Conversion Details:**
```
Total Lines Processed: 146202
Comment Lines: 15
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 146185
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

## CERT.PL's Warning List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [certpl.list](https://mili-tan.github.io/justdomains/lists/certpl.list) |
| Pi-Hole | [certpl.list](https://mili-tan.github.io/justdomains/lists/certpl.list) |

**Source:** [https://hole.cert.pl/domains/domains_adblock.txt](https://hole.cert.pl/domains/domains_adblock.txt)
- Title: CERT.PL's Warning List
- Version: 202505101613
- Homepage: [https://cert.pl/news/single/ostrzezenia_phishing/](https://cert.pl/news/single/ostrzezenia_phishing/)

**Conversion Details:**
```
Total Lines Processed: 309339
Comment Lines: 4
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 309334
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 0
```

&nbsp;

## Hagezi Anti Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |
| Pi-Hole | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- Title: HaGeZi's Encrypted DNS/VPN/TOR/Proxy Bypass DNS Blocklist
- Version: 2025.0510.1400.53
- Last Modified: 10 May 2025 14:00 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 4071
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 4058
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
