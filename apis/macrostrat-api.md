# Macrostrat API

Macrostrat is a platform for the aggregation and distribution of geological data relevant to the spatial and temporal distribution of sedimentary, igneous, and metamorphic rocks, as well as data extracted from them. The API exposes columns, units, sections, fossils, geologic map units, paleogeography reconstructions, measurements, statistics, and cartography services.

## Base URL

`https://macrostrat.org/api/v2`

## License

Macrostrat data is released under CC-BY 4.0.

## Endpoints

| Endpoint | Description |
|----------|-------------|
| `/columns` | Search and summarize columns by unit properties or geographic location. |
| `/sections` | Summarize units by gap-bound packages. |
| `/units` | Query Macrostrat units matching criteria. |
| `/fossils` | Paleobiology Database collections matched to Macrostrat units. |
| `/stats` | Database statistics. |
| `/paleogeography` | Paleogeography geometry (Wright et al. 2013). |
| `/geologic_units/map` | Geologic map units from various sources. |
| `/geologic_units/map/points` | Point features from geologic maps. |
| `/geologic_units/map/legend` | Legend data for geologic map units. |
| `/measurements` | Measurement data. |
| `/age_model` | Column age model components. |
| `/defs` | Standard fields and dictionaries. |
| `/carto` | Geologic map creation routes. |
| `/grids` | Grid data queries. |
| `/mobile` | Simplified data delivery for mobile clients. |
| `/meta` | API metadata. |

## Format Support

Many endpoints support `format=json|csv|geojson|topojson`.

## Reference

- [Macrostrat](https://macrostrat.org)
- [API v2 Reference](https://macrostrat.org/api/v2)
