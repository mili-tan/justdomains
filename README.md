# DOMAIN-ONLY Filter Lists
**Last Updated:** 2026-09-05 17:51:14

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [AdAway Blocklist](#adaway-blocklist-domains-only) (Domains-only)
  - [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) (Domains-only)
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
  - [A-Dove-is-dumb](#a-dove-is-dumb-domains-only) (Domains-only)
  - [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) (Domains-only)
  - [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) (Domains-only)
  - [HideMyTel](#hidemytel-domains-only) (Domains-only)
  - [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) (Domains-only)
  - [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) (Domains-only)
  - [Anti-AD PCDN](#anti-ad-pcdn-domains-only) (Domains-only)
  - [KAD](#kad-domains-only) (Domains-only)
  - [uBlock Badware Risks Filters](#ublock-badware-risks-filters-domains-only) (Domains-only)
  - [Iam-py-test's Antitypo List](#iam-py-tests-antitypo-list-domains-only) (Domains-only)
  - [Iam-py-test's AntiIpLookup List](#iam-py-tests-antiiplookup-list-domains-only) (Domains-only)
  - [GOODBYEADS](#goodbyeads-domains-only) (Domains-only)
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
| [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) | MIT | 79996 | [**Download**](https://mili-tan.github.io/justdomains/lists/stevenblack.list) | 04 September 2026 13:35:23 (UTC) |
| [AdRules DNS List](#adrules-dns-list-domains-only) | WTFPL | 199057 | [**Download**](https://mili-tan.github.io/justdomains/lists/adrules.list) |  |
| [AdGuard DNS Filter](#adguard-dns-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 179340 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2026-09-05T16:13:13.230Z |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 49295 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 05 Sep 2026 17:39 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 46621 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 05 Sep 2026 17:39 UTC |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 154 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2026/03/11 09:15 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](https://easylist.to/pages/licence.html) | 867 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 05 Sep 2026 17:42 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 6069 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 05 Sep 2026 17:41 UTC |
| [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 102318 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AWAvenue Ads Rule](#awavenue-ads-rule-domains-only) | CC BY-NC-SA 4.0 | 897 | [**Download**](https://mili-tan.github.io/justdomains/lists/awavenue.list) |  |
| [OISD Small](#oisd-small-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 63295 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) | 2026-09-05T13:06:15+0000 |
| [OISD Big](#oisd-big-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 256828 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdbig.list) | 2026-09-05T17:05:25+0000 |
| [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 37702 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi.list) | 05 Sep 2026 15:16 UTC |
| [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 192739 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) | 05 Sep 2026 15:12 UTC |
| [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) | GPL2 | 281369 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7.list) |  |
| [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) | GPL2 | 37692 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7l.list) |  |
| [1Hosts Lite](#1hosts-lite-domains-only) | MPL-2.0 | 3475 | [**Download**](https://mili-tan.github.io/justdomains/lists/1hl.list) | 2025-12-25T07:47:56.856Z |
| [NoCoin Filter](#nocoin-filter-domains-only) | [MIT](https://mit-license.org/) | 313 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 05 March 2025 |
| [Prigent Crypto](#prigent-crypto-domains-only) | CC BY-SA 4.0 | 11491 | [**Download**](https://mili-tan.github.io/justdomains/lists/coinblocker.list) |  |
| [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) | [GPL3](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 16963 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) | 05 Sep 2026 15:55 UTC |
| [DDNS Filter](#ddns-filter-domains-only) | Unlicense | 39271 | [**Download**](https://mili-tan.github.io/justdomains/lists/ddns.list) |  |
| [IPFS Filter](#ipfs-filter-domains-only) | MIT | 77 | [**Download**](https://mili-tan.github.io/justdomains/lists/ipfs.list) |  |
| [Search Filter](#search-filter-domains-only) | MIT | 172 | [**Download**](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |  |
| [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) | MIT | 98 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |  |
| [Hagezi Mobile Native Tracking Filter](#hagezi-mobile-native-tracking-filter-domains-only) | GPL3 | 1501 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativemobile.list) |  |
| [Hagezi Software Native Tracking Filter](#hagezi-software-native-tracking-filter-domains-only) | GPL3 | 1192 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativesoft.list) |  |
| [Hagezi TV Native Tracking Filter](#hagezi-tv-native-tracking-filter-domains-only) | GPL3 | 413 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetv.list) |  |
| [A-Dove-is-dumb](#a-dove-is-dumb-domains-only) | BSD-2-Clause | 5677 | [**Download**](https://mili-tan.github.io/justdomains/lists/a-dove-is-dumb.list) | 2026-09-03 02:02 UTC |
| [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) | GPL2 | 165 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |  |
| [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) | GPL3 | 35 | [**Download**](https://mili-tan.github.io/justdomains/lists/httpdns.list) |  |
| [HideMyTel](#hidemytel-domains-only) | MIT | 23 | [**Download**](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |  |
| [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) | MIT | 73 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |  |
| [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) | MIT | 13 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |  |
| [Anti-AD PCDN](#anti-ad-pcdn-domains-only) | MIT | 30 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |  |
| [KAD](#kad-domains-only) | CC BY-SA 4.0 | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/kad.list) | Sat, 05 Sep 2026, 19:45 UTC+02:00 |
| [uBlock Badware Risks Filters](#ublock-badware-risks-filters-domains-only) | [GPL3](https://github.com/uBlockOrigin/uAssets/blob/master/LICENSE) | 50 | [**Download**](https://mili-tan.github.io/justdomains/lists/ubbadware.list) | %timestamp% |
| [Iam-py-test's Antitypo List](#iam-py-tests-antitypo-list-domains-only) | CC0-1.0 | 774 | [**Download**](https://mili-tan.github.io/justdomains/lists/antitypo.list) | 2026-3-26 |
| [Iam-py-test's AntiIpLookup List](#iam-py-tests-antiiplookup-list-domains-only) | CC0-1.0 | 98 | [**Download**](https://mili-tan.github.io/justdomains/lists/antiiplookup.list) |  |
| [GOODBYEADS](#goodbyeads-domains-only) | MIT | 116836 | [**Download**](https://mili-tan.github.io/justdomains/lists/goodbyeads.list) |  |

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
- Last Modified: 04 September 2026 13:35:23 (UTC)

**Conversion Details:**
```
Total Lines Processed: 86813
Comment Lines: 4272
Empty Lines: 2533
Invalid Lines: 0
Non-Loopback Lines (Ignored): 7
Local Hosts (Ignored): 4
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 79996
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
Total Lines Processed: 199504
Comment Lines: 9
Empty Lines: 0
Non-Domain-only Rules Excluded: 438
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 199057
```

&nbsp;

## AdGuard DNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.1.33.64
- Last Modified: 2026-09-05T16:13:13.230Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 181977
Comment Lines: 1602
Empty Lines: 0
Non-Domain-only Rules Excluded: 952
Domain-only Rules Excluded (unsupported options): 6
Domain-only Rules Excluded (exception conflict): 77
Domain-only Rules Output: 179340
```

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202609051739
- Last Modified: 05 Sep 2026 17:39 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 81801
Comment Lines: 278
Empty Lines: 0
Non-Domain-only Rules Excluded: 28836
Domain-only Rules Excluded (unsupported options): 3323
Domain-only Rules Excluded (exception conflict): 69
Domain-only Rules Output: 49295
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202609051739
- Last Modified: 05 Sep 2026 17:39 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 56805
Comment Lines: 770
Empty Lines: 0
Non-Domain-only Rules Excluded: 8987
Domain-only Rules Excluded (unsupported options): 234
Domain-only Rules Excluded (exception conflict): 193
Domain-only Rules Output: 46621
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202603110915
- Last Modified: 2026/03/11 09:15 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1861
Comment Lines: 20
Empty Lines: 0
Non-Domain-only Rules Excluded: 1678
Domain-only Rules Excluded (unsupported options): 8
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 154
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202609051742
- Last Modified: 05 Sep 2026 17:42 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 50521
Comment Lines: 1378
Empty Lines: 0
Non-Domain-only Rules Excluded: 48158
Domain-only Rules Excluded (unsupported options): 71
Domain-only Rules Excluded (exception conflict): 47
Domain-only Rules Output: 867
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202609051741
- Last Modified: 05 Sep 2026 17:41 UTC
- Homepage: [https://github.com/easylist/easylistchina/](https://github.com/easylist/easylistchina/)

**Conversion Details:**
```
Total Lines Processed: 19462
Comment Lines: 107
Empty Lines: 0
Non-Domain-only Rules Excluded: 13119
Domain-only Rules Excluded (unsupported options): 155
Domain-only Rules Excluded (exception conflict): 12
Domain-only Rules Output: 6069
```

&nbsp;

## AdGuard Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.1.10.84
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 330885
Comment Lines: 3601
Empty Lines: 0
Non-Domain-only Rules Excluded: 219925
Domain-only Rules Excluded (unsupported options): 701
Domain-only Rules Excluded (exception conflict): 4340
Domain-only Rules Output: 102318
```

&nbsp;

## AWAvenue Ads Rule (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |
| Pi-Hole | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |

**Source:** [https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- Title: AWAvenue Ads Rule
- Version: 1.7.6-release

**Conversion Details:**
```
Total Lines Processed: 913
Comment Lines: 8
Empty Lines: 3
Non-Domain-only Rules Excluded: 8
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 897
```

&nbsp;

## OISD Small (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |
| Pi-Hole | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |

**Source:** [https://small.oisd.nl](https://small.oisd.nl)
- Title: oisd small
- Version: 202609051306
- Last Modified: 2026-09-05T13:06:15+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 63307
Comment Lines: 10
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 63295
```

&nbsp;

## OISD Big (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |
| Pi-Hole | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |

**Source:** [https://big.oisd.nl](https://big.oisd.nl)
- Title: oisd big
- Version: 202609051705
- Last Modified: 2026-09-05T17:05:25+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 256840
Comment Lines: 10
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 256828
```

&nbsp;

## Hagezi Blocklists Light (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |
| Pi-Hole | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)
- Title: HaGeZi's Multi LIGHT - basic protection
- Version: 2026.0905.1516.02
- Last Modified: 05 Sep 2026 15:16 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 37716
Comment Lines: 13
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37702
```

&nbsp;

## Hagezi Blocklists Normal (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |
| Pi-Hole | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)
- Title: HaGeZi's Multi NORMAL - all-round protection
- Version: 2026.0905.1512.23
- Last Modified: 05 Sep 2026 15:12 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 192753
Comment Lines: 13
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 192739
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
Total Lines Processed: 281583
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 209
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 281369
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
Total Lines Processed: 37699
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37692
```

&nbsp;

## 1Hosts Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [1hl.list](https://mili-tan.github.io/justdomains/lists/1hl.list) |
| Pi-Hole | [1hl.list](https://mili-tan.github.io/justdomains/lists/1hl.list) |

**Source:** [https://o0.pages.dev/Lite/adblock.txt](https://o0.pages.dev/Lite/adblock.txt)
- Title: 1Hosts (Lite)
- Last Modified: 2025-12-25T07:47:56.856Z
- Homepage: [https://github.com/badmojr/1Hosts](https://github.com/badmojr/1Hosts)

**Conversion Details:**
```
Total Lines Processed: 3491
Comment Lines: 15
Empty Lines: 1
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 3475
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
Total Lines Processed: 11491
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 11491
```

&nbsp;

## Hagezi Anti Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |
| Pi-Hole | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- Title: HaGeZi's Encrypted DNS/VPN/TOR/Proxy Bypass - stop people from sneaking around your DNS!
- Version: 2026.0905.1555.24
- Last Modified: 05 Sep 2026 15:55 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 16977
Comment Lines: 13
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 16963
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
Total Lines Processed: 39271
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 39271
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
Total Lines Processed: 172
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 172
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
Total Lines Processed: 1501
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 1501
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
Total Lines Processed: 1192
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 1192
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
Total Lines Processed: 413
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 413
```

&nbsp;

## A-Dove-is-dumb (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [a-dove-is-dumb.list](https://mili-tan.github.io/justdomains/lists/a-dove-is-dumb.list) |
| Pi-Hole | [a-dove-is-dumb.list](https://mili-tan.github.io/justdomains/lists/a-dove-is-dumb.list) |

**Source:** [https://raw.githubusercontent.com/ignaciocastro/a-dove-is-dumb/refs/heads/main/winhosts.txt](https://raw.githubusercontent.com/ignaciocastro/a-dove-is-dumb/refs/heads/main/winhosts.txt)
- Last Modified: 2026-09-03 02:02 UTC

**Conversion Details:**
```
Total Lines Processed: 5705
Comment Lines: 28
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 5677
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
Total Lines Processed: 35
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 35
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
Total Lines Processed: 73
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 73
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
- Title: 馃嚨馃嚤 KAD - STOP Przekr臋tom
- Version: 2026.9.5.2
- Last Modified: Sat, 05 Sep 2026, 19:45 UTC+02:00
- Homepage: [https://kadantiscam.netlify.app](https://kadantiscam.netlify.app)

**Conversion Details:**
```
Total Lines Processed: 21393
Comment Lines: 49
Empty Lines: 0
Non-Domain-only Rules Excluded: 321
Domain-only Rules Excluded (unsupported options): 21023
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 0
```

&nbsp;

## uBlock Badware Risks Filters (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [ubbadware.list](https://mili-tan.github.io/justdomains/lists/ubbadware.list) |
| Pi-Hole | [ubbadware.list](https://mili-tan.github.io/justdomains/lists/ubbadware.list) |

**Source:** [https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt)
- Title: uBlock鈧 filters 鈥 Badware risks
- Last Modified: %timestamp%
- Homepage: [https://github.com/uBlockOrigin/uAssets](https://github.com/uBlockOrigin/uAssets)

**Conversion Details:**
```
Total Lines Processed: 6493
Comment Lines: 1598
Empty Lines: 529
Non-Domain-only Rules Excluded: 2016
Domain-only Rules Excluded (unsupported options): 2829
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 50
```

&nbsp;

## Iam-py-test's Antitypo List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [antitypo.list](https://mili-tan.github.io/justdomains/lists/antitypo.list) |
| Pi-Hole | [antitypo.list](https://mili-tan.github.io/justdomains/lists/antitypo.list) |

**Source:** [https://raw.githubusercontent.com/iam-py-test/my_filters_001/refs/heads/main/Alternative%20list%20formats/antitypo_hosts.txt](https://raw.githubusercontent.com/iam-py-test/my_filters_001/refs/heads/main/Alternative%20list%20formats/antitypo_hosts.txt)
- Title: iam-py-test's antitypo list
- Last Modified: 2026-3-26
- Homepage: [https://github.com/iam-py-test/my_filters_001](https://github.com/iam-py-test/my_filters_001)

**Conversion Details:**
```
Total Lines Processed: 1088
Comment Lines: 310
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 4
Duplicate Hosts (Ignored): 0
Hosts Output: 774
```

&nbsp;

## Iam-py-test's AntiIpLookup List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [antiiplookup.list](https://mili-tan.github.io/justdomains/lists/antiiplookup.list) |
| Pi-Hole | [antiiplookup.list](https://mili-tan.github.io/justdomains/lists/antiiplookup.list) |

**Source:** [https://raw.githubusercontent.com/iam-py-test/my_filters_001/refs/heads/main/antiiplookup.txt](https://raw.githubusercontent.com/iam-py-test/my_filters_001/refs/heads/main/antiiplookup.txt)
- Title: IP Lookup service blocklist

**Conversion Details:**
```
Total Lines Processed: 156
Comment Lines: 56
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 2
Hosts Output: 98
```

&nbsp;

## GOODBYEADS (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [goodbyeads.list](https://mili-tan.github.io/justdomains/lists/goodbyeads.list) |
| Pi-Hole | [goodbyeads.list](https://mili-tan.github.io/justdomains/lists/goodbyeads.list) |

**Source:** [https://raw.githubusercontent.com/8680/GOODBYEADS/master/data/rules/dns.txt](https://raw.githubusercontent.com/8680/GOODBYEADS/master/data/rules/dns.txt)
- Title: GOODBYEADS
- Version: 2026-09-05 22:54:33锛堝寳浜椂闂达級
- Homepage: [https://github.com/8680/GOODBYEADS](https://github.com/8680/GOODBYEADS)

**Conversion Details:**
```
Total Lines Processed: 117208
Comment Lines: 6
Empty Lines: 0
Non-Domain-only Rules Excluded: 366
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 116836
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
