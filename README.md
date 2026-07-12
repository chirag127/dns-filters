# dns-filters

[![Stars](https://img.shields.io/github/stars/chirag127/dns-filters?style=flat&logo=github)](https://github.com/chirag127/dns-filters/stargazers)

Personal DNS blocklist — paywall engines, tracker SDKs, and ad loaders.

Site: [dns-filters.oriz.in](https://dns-filters.oriz.in)

## Files

| File                         | Format                              | Compatible with                                                                   |
| ---------------------------- | ----------------------------------- | --------------------------------------------------------------------------------- |
| [`adblock.txt`](adblock.txt) | AdGuard/uBlock `\|\|domain^` syntax | AdGuard Home, AdGuard DNS custom rules, NextDNS custom, uBlock Origin, Pi-hole v6 |
| [`domains.txt`](domains.txt) | Plain domain per line               | NextDNS custom blocklist URL, most resolvers                                      |
| [`hosts.txt`](hosts.txt)     | `0.0.0.0 domain` hosts format       | `/etc/hosts`, Pi-hole, AdGuard Home, StevenBlack aggregator                       |

## Raw URLs

```
https://raw.githubusercontent.com/chirag127/dns-filters/main/adblock.txt
https://raw.githubusercontent.com/chirag127/dns-filters/main/domains.txt
https://raw.githubusercontent.com/chirag127/dns-filters/main/hosts.txt
```

## How to use

### AdGuard Home

Settings → Filters → DNS blocklists → Add blocklist → paste the `adblock.txt` raw URL.

### NextDNS

Security → Add a blocklist → Custom → paste the `domains.txt` raw URL.

### Pi-hole

Group Management → Adlists → paste the `adblock.txt` or `hosts.txt` raw URL.

### uBlock Origin

Dashboard → Filter lists → Import → paste the `adblock.txt` raw URL.

## Domains blocked

| Domain                           | Category                                 |
| -------------------------------- | ---------------------------------------- |
| `blueconic.net`                  | Paywall / metered-access engine          |
| `*.cdn.registerdisney.go.com`    | Paywall SDK                              |
| `*.cnv-medien.de`                | Paywall engine (German press)            |
| `*.cxense.com`                   | Tracker / paywall analytics              |
| `*.ev.lavanguardia.com`          | Paywall (La Vanguardia)                  |
| `*.ev.mundodeportivo.com`        | Paywall (Mundo Deportivo)                |
| `*.evolok.net`                   | Paywall engine                           |
| `*.flowerstreatment.com`         | Paywall / metered access                 |
| `*.guidecent.com`                | Paywall SDK                              |
| `*.hadrianpaywall.com`           | Hadrian paywall engine                   |
| `*.htlbid.com`                   | Ad bid loader                            |
| `*.jerseyeveningpost.com`        | Paywall (Jersey Evening Post)            |
| `*.js.matheranalytics.com`       | Paywall analytics (Mather Economics)     |
| `*.js.pelcro.com`                | Pelcro paywall SDK                       |
| `*.lapost.com`                   | Paywall                                  |
| `*.loader.newsday.com`           | Paywall loader (Newsday)                 |
| `*.lrb.co.uk`                    | Paywall (London Review of Books)         |
| `*.moscout.com`                  | Paywall / metered access                 |
| `*.olytics.omeda.com`            | Paywall analytics (Omeda)                |
| `*.onecount.net`                 | OneCount paywall engine                  |
| `*.paywall.correiodopovo.com.br` | Paywall (Correio do Povo)                |
| `*.paywall.folha.uol.com.br`     | Paywall (Folha de S.Paulo)               |
| `*.poool.fr`                     | Poool paywall engine (French press)      |
| `*.qiota.com`                    | Qiota paywall SDK                        |
| `*.rdhmag.com`                   | Paywall (RDH magazine)                   |
| `*.sophi.io`                     | Sophi.io paywall engine (Globe and Mail) |
| `*.steadyhq.com`                 | Steady subscription paywall              |
| `*.theintercept.com`             | Paywall (The Intercept)                  |
| `*.thetablet.org`                | Paywall (The Tablet)                     |
| `*.zonda.clarin.com`             | Paywall (Clarín)                         |
| `*.adconfig.wynk.in`             | Ad config SDK (Wynk)                     |

## License

CC0-1.0 — public domain. No attribution required.
