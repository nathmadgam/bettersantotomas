# Better Santo Tomas

A community-run portal for **Santo Tomas, Pangasinan**: municipal officials, offices, services and public information in one place.

Better Santo Tomas is a volunteer project listed in the [BetterGov.ph LGU Directory](https://lgu.bettergov.ph/). It is **not** an official website of the Municipality of Santo Tomas.

## About Santo Tomas

Santo Tomas is a landlocked municipality in the fifth congressional district of Pangasinan, Ilocos Region, with 10 barangays and a 2020 census population of 14,878. It is an agricultural town producing palay, yellow corn, coconut and tobacco, and it holds a Guinness World Records title for the longest barbecue, set in 2008.

| Barangay | Population (2020) |
|---|---|
| La Luna | 922 |
| Poblacion East | 991 |
| Poblacion West | 585 |
| Salvacion | 1,509 |
| San Agustin | 1,570 |
| San Antonio | 4,282 |
| San Jose | 1,340 |
| San Marcos | 881 |
| Santo Domingo | 1,584 |
| Santo Niño | 1,214 |

Sources: [PhilAtlas (PSA data)](https://www.philatlas.com/luzon/r01/pangasinan/santo-tomas.html), [Rappler 2025 election results (unofficial count)](https://ph.rappler.com/elections/2025/local-race/pangasinan/santo-tomas).

## Run it locally

Requires Node.js 18 or newer.

```bash
npm install
npm run dev
```

Then open http://localhost:5173.

Site content lives in `content/` (Markdown and YAML) and `src/data/`. See [CONTENT-MANAGEMENT.md](CONTENT-MANAGEMENT.md) for how to edit pages without touching code.

## Contributing

Many service pages are still placeholders. If you know how a service works in Santo Tomas (requirements, office, fees, schedule), open an issue or a pull request. Please cite a public source for facts about officials, offices and fees.

## Credits

Built on the [Better Local Gov](https://github.com/iyanski/betterlocalgov) starter kit by the BetterGov.ph community. Released under [CC0 1.0](LICENSE).
