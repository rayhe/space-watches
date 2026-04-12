# 🚀⌚ Space Watches Database

**Every watch worn in space: 2,167 records from 1965–2025.**

A comprehensive database of watches worn by astronauts and cosmonauts during spaceflight, covering 60 years of missions from Voskhod 2 through Blue Origin NS-37.

## [🔍 Browse the Database →](https://rayhe.github.io/space-watches/)

## Key Stats

| Metric | Value |
|--------|-------|
| Total records | 2,167 |
| Date range | 1965 – 2025 |
| Unique astronauts | ~600+ |
| Watch brands | 40+ |
| Countries | 20+ |
| Programs | 13 (Gemini through Blue Origin) |

## Top Brands

| Brand | Count | % |
|-------|-------|---|
| Omega | 760 | 35.1% |
| Casio | 421 | 19.4% |
| Seiko | 225 | 10.4% |
| Timex | 113 | 5.2% |
| Breitling | 30 | 1.4% |
| Rolex | 25 | 1.2% |

## Files

- **[data.json](data.json)** — Full dataset in JSON format
- **[data.csv](data.csv)** — Full dataset in CSV format
- **[index.html](index.html)** — Interactive searchable website

## Field Definitions

| Field | Description |
|-------|-------------|
| `id` | Sequential record number |
| `astronaut` | Astronaut/cosmonaut name |
| `country` | Country of origin |
| `mission` | Mission designation (e.g., STS-120, Gemini IV) |
| `date` | Mission date (YYYY-MM-DD or YYYY) |
| `year` | Mission year |
| `decade` | Decade (1960s, 1970s, etc.) |
| `program` | Space program (Gemini, Apollo, Space Shuttle, etc.) |
| `notes` | Mission notes and watch details |
| `watch_brand` | Watch manufacturer |
| `watch_model` | Watch model name/number |
| `reference` | Reference number or additional details |
| `wrist` | Wrist position (Left, Right, Outside Suit, etc.) |
| `image_url` | Primary watch/astronaut image URL |
| `source_urls` | Source references |

## Data Source

This data was compiled by **Robert Jackson** and the [Space Watches Facebook Group](https://www.facebook.com/groups/spacewatches/). The original dataset is hosted on [Google Looker Studio](https://lookerstudio.google.com/u/0/reporting/40738bd5-c07f-41f2-aaad-ca5b0aaf9602/page/ZNSUB).

## License

Data compiled by Robert Jackson. This repository provides the data in accessible formats for research and reference. Images are hosted by their original sources (rjjackson.com, NASA, Smithsonian, etc.).
