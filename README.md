# DOMAIN-ONLY Filter Lists
**Last Updated:** 2021-07-13 00:36:00

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [EasyList](#easylist-domains-only) (Domains-only)
  - [EasyPrivacy](#easyprivacy-domains-only) (Domains-only)
  - [Fanboy's Social Blocking](#fanboys-social-blocking-domains-only) (Domains-only)
  - [CJX's EasyList Lite](#cjxs-easylist-lite-domains-only) (Domains-only)
  - [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) (Domains-only)
  - [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) (Domains-only)
  - [EasyList China](#easylist-china-domains-only) (Domains-only)
  - [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) (Domains-only)
  - [AdGuard Base Filter](#adguard-base-filter-domains-only) (Domains-only)
  - [AdGuard Tracking Protection filter](#adguard-tracking-protection-filter-domains-only) (Domains-only)
  - [AdGuard Social media filter](#adguard-social-media-filter-domains-only) (Domains-only)
  - [AdGuard Annoyances filter](#adguard-annoyances-filter-domains-only) (Domains-only)
  - [AdGuard Chinese filter](#adguard-chinese-filter-domains-only) (Domains-only)
  - [AdGuard Mobile ads filter](#adguard-mobile-ads-filter-domains-only) (Domains-only)
  - [NoCoin Filter List](#nocoin-filter-list-domains-only) (Domains-only)
  - [AdAway default blocklist](#adaway-default-blocklist-domains-only) (Domains-only)
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
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 15415 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 13 Jul 2021 00:21 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 16152 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 13 Jul 2021 00:21 UTC |
| [Fanboy's Social Blocking](#fanboys-social-blocking-domains-only) | [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) | 101 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-social.list) | 13 Jul 2021 00:33 UTC |
| [CJX's EasyList Lite](#cjxs-easylist-lite-domains-only) | [LGPL-3.0 License](https://easylist-downloads.adblockplus.org/COPYING) | 20 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjxlist.list) | 2020/12/08 08:56 +0800 |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0 License](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 160 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2021/06/13 17:22 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) | 698 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 13 Jul 2021 00:21 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist-downloads.adblockplus.org/COPYING) | 5343 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 13 Jul 2021 00:23 UTC |
| [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 37103 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2021-07-13T00:14:28.439Z |
| [AdGuard Base Filter](#adguard-base-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 1217 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-base.list) |  |
| [AdGuard Tracking Protection filter](#adguard-tracking-protection-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 16166 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AdGuard Social media filter](#adguard-social-media-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 43 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-social.list) |  |
| [AdGuard Annoyances filter](#adguard-annoyances-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 639 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-annoyances.list) |  |
| [AdGuard Chinese filter](#adguard-chinese-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 5578 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-chinese.list) |  |
| [AdGuard Mobile ads filter](#adguard-mobile-ads-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 981 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-mobile.list) |  |
| [NoCoin Filter List](#nocoin-filter-list-domains-only) | [MIT](https://github.com/hoshsadiq/adblock-nocoin-list/blob/master/LICENSE) | 689 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 20 Jan 2021 |
| [AdAway default blocklist](#adaway-default-blocklist-domains-only) | [CC Attribution 3.0](https://github.com/AdAway/AdAway/blob/master/LICENSE) | 8224 | [**Download**](https://mili-tan.github.io/justdomains/lists/adaway.list) |  |

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202107130021
- Last Modified: 13 Jul 2021 00:21 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 56411
Comment Lines: 264
Empty Lines: 0
Non-Domain-only Rules Excluded: 39094
Domain-only Rules Excluded (unsupported options): 1589
Domain-only Rules Excluded (exception conflict): 49
Domain-only Rules Output: 15415
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202107130021
- Last Modified: 13 Jul 2021 00:21 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 27885
Comment Lines: 461
Empty Lines: 0
Non-Domain-only Rules Excluded: 10918
Domain-only Rules Excluded (unsupported options): 222
Domain-only Rules Excluded (exception conflict): 132
Domain-only Rules Output: 16152
```

&nbsp;

## Fanboy's Social Blocking (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-social.list](https://mili-tan.github.io/justdomains/lists/fanboy-social.list) |
| Pi-Hole | [fanboy-social.list](https://mili-tan.github.io/justdomains/lists/fanboy-social.list) |

**Source:** [https://easylist.to/easylist/fanboy-social.txt](https://easylist.to/easylist/fanboy-social.txt)
- Title: Fanboy's Social Blocking List
- Version: 202107130033
- Last Modified: 13 Jul 2021 00:33 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 20377
Comment Lines: 140
Empty Lines: 0
Non-Domain-only Rules Excluded: 20117
Domain-only Rules Excluded (unsupported options): 10
Domain-only Rules Excluded (exception conflict): 9
Domain-only Rules Output: 101
```

&nbsp;

## CJX's EasyList Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjxlist.list](https://mili-tan.github.io/justdomains/lists/cjxlist.list) |
| Pi-Hole | [cjxlist.list](https://mili-tan.github.io/justdomains/lists/cjxlist.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjxlist.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjxlist.txt)
- Title: CJX's EasyList Lite
- Version: 202012080856
- Last Modified: 2020/12/08 08:56 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 527
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 494
Domain-only Rules Excluded (unsupported options): 1
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 20
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202106131722
- Last Modified: 2021/06/13 17:22 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1736
Comment Lines: 51
Empty Lines: 0
Non-Domain-only Rules Excluded: 1517
Domain-only Rules Excluded (unsupported options): 7
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 160
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202107130021
- Last Modified: 13 Jul 2021 00:21 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 49032
Comment Lines: 573
Empty Lines: 0
Non-Domain-only Rules Excluded: 47674
Domain-only Rules Excluded (unsupported options): 51
Domain-only Rules Excluded (exception conflict): 36
Domain-only Rules Output: 698
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202107130023
- Last Modified: 13 Jul 2021 00:23 UTC
- Homepage: [http://abpchina.org/forum/](http://abpchina.org/forum/)

**Conversion Details:**
```
Total Lines Processed: 18989
Comment Lines: 105
Empty Lines: 0
Non-Domain-only Rules Excluded: 13296
Domain-only Rules Excluded (unsupported options): 224
Domain-only Rules Excluded (exception conflict): 21
Domain-only Rules Output: 5343
```

&nbsp;

## AdGuard Simplified Domain Names Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.21.69
- Last Modified: 2021-07-13T00:14:28.439Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 38258
Comment Lines: 580
Empty Lines: 0
Non-Domain-only Rules Excluded: 536
Domain-only Rules Excluded (unsupported options): 5
Domain-only Rules Excluded (exception conflict): 34
Domain-only Rules Output: 37103
```

&nbsp;

## AdGuard Base Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-base.list](https://mili-tan.github.io/justdomains/lists/adguard-base.list) |
| Pi-Hole | [adguard-base.list](https://mili-tan.github.io/justdomains/lists/adguard-base.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/2.txt](https://filters.adtidy.org/extension/chromium/filters/2.txt)
- Title: AdGuard Base filter
- Version: 2.1.84.72
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 100344
Comment Lines: 11949
Empty Lines: 0
Non-Domain-only Rules Excluded: 67909
Domain-only Rules Excluded (unsupported options): 2126
Domain-only Rules Excluded (exception conflict): 17143
Domain-only Rules Output: 1217
```

&nbsp;

## AdGuard Tracking Protection filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.26.60
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 22974
Comment Lines: 1866
Empty Lines: 0
Non-Domain-only Rules Excluded: 4602
Domain-only Rules Excluded (unsupported options): 100
Domain-only Rules Excluded (exception conflict): 240
Domain-only Rules Output: 16166
```

&nbsp;

## AdGuard Social media filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-social.list](https://mili-tan.github.io/justdomains/lists/adguard-social.list) |
| Pi-Hole | [adguard-social.list](https://mili-tan.github.io/justdomains/lists/adguard-social.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/4.txt](https://filters.adtidy.org/extension/chromium/filters/4.txt)
- Title: AdGuard Social Media filter
- Version: 2.0.43.21
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 9638
Comment Lines: 555
Empty Lines: 0
Non-Domain-only Rules Excluded: 9032
Domain-only Rules Excluded (unsupported options): 4
Domain-only Rules Excluded (exception conflict): 4
Domain-only Rules Output: 43
```

&nbsp;

## AdGuard Annoyances filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-annoyances.list](https://mili-tan.github.io/justdomains/lists/adguard-annoyances.list) |
| Pi-Hole | [adguard-annoyances.list](https://mili-tan.github.io/justdomains/lists/adguard-annoyances.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/14.txt](https://filters.adtidy.org/extension/chromium/filters/14.txt)
- Title: AdGuard Annoyances filter
- Version: 2.0.86.96
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 27220
Comment Lines: 3754
Empty Lines: 0
Non-Domain-only Rules Excluded: 22710
Domain-only Rules Excluded (unsupported options): 85
Domain-only Rules Excluded (exception conflict): 32
Domain-only Rules Output: 639
```

&nbsp;

## AdGuard Chinese filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-chinese.list](https://mili-tan.github.io/justdomains/lists/adguard-chinese.list) |
| Pi-Hole | [adguard-chinese.list](https://mili-tan.github.io/justdomains/lists/adguard-chinese.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/224.txt](https://filters.adtidy.org/extension/chromium/filters/224.txt)
- Title: AdGuard Chinese filter
- Version: 2.0.29.17
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 20692
Comment Lines: 441
Empty Lines: 0
Non-Domain-only Rules Excluded: 14402
Domain-only Rules Excluded (unsupported options): 250
Domain-only Rules Excluded (exception conflict): 21
Domain-only Rules Output: 5578
```

&nbsp;

## AdGuard Mobile ads filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-mobile.list](https://mili-tan.github.io/justdomains/lists/adguard-mobile.list) |
| Pi-Hole | [adguard-mobile.list](https://mili-tan.github.io/justdomains/lists/adguard-mobile.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/11.txt](https://filters.adtidy.org/extension/chromium/filters/11.txt)
- Title: AdGuard Mobile Ads filter
- Version: 2.0.21.0
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 4704
Comment Lines: 943
Empty Lines: 0
Non-Domain-only Rules Excluded: 2742
Domain-only Rules Excluded (unsupported options): 24
Domain-only Rules Excluded (exception conflict): 14
Domain-only Rules Output: 981
```

&nbsp;

## NoCoin Filter List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |
| Pi-Hole | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 20 Jan 2021
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 706
Comment Lines: 10
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 6
Hosts Output: 689
```

&nbsp;

## AdAway default blocklist (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |
| Pi-Hole | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |

**Source:** [https://adaway.org/hosts.txt](https://adaway.org/hosts.txt)

**Conversion Details:**
```
Total Lines Processed: 12344
Comment Lines: 2068
Empty Lines: 2049
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 2
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 1
Hosts Output: 8224
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
