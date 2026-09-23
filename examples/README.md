# examples/

Live responses captured from University of Gothenburg surfaces on **2026-09-01**.

`method: probed` — every file here is a real HTTP response body, not a hand-written sample.
Where a response was too large to store whole it was **truncated, never edited**, and the file
says so in a `_truncated` key naming the full count.

| File | Request | Status | Operator |
|---|---|---|---|
| `university-of-gothenburg-gupea-oai-identify-example.xml` | `GET https://gupea.ub.gu.se/server/oai/request?verb=Identify` | 200 text/xml | institution |
| `university-of-gothenburg-gupea-oai-metadata-formats-example.xml` | `GET https://gupea.ub.gu.se/server/oai/request?verb=ListMetadataFormats` | 200 text/xml | institution |
| `university-of-gothenburg-gupea-dspace-rest-root-example.json` | `GET https://gupea.ub.gu.se/server/api` | 200 application/hal+json | institution |
| `university-of-gothenburg-idp-saml-metadata-example.xml` | `GET https://mds.swamid.se/entities/https%3A%2F%2Fidp3.it.gu.se%2Fidp%2Fshibboleth` | 200 application/samlmetadata+xml | federation |
| `university-of-gothenburg-korp-info-example.json` | `GET https://ws.spraakbanken.gu.se/ws/korp/v8/info` | 200 application/json | institution |
| `university-of-gothenburg-metadata-list-ids-example.json` | `GET https://ws.spraakbanken.gu.se/ws/metadata/v3/list-ids` | 200 application/json | institution |
| `university-of-gothenburg-karp-search-config-example.json` | `GET https://spraakbanken4.it.gu.se/karps/v1/config` | 200 application/json | institution |
| `university-of-gothenburg-mink-info-example.json` | `GET https://ws.spraakbanken.gu.se/ws/mink/v3/info` | 200 application/json | institution |
| `university-of-gothenburg-sparv-ping-example.json` | `GET https://ws.spraakbanken.gu.se/ws/sparv/v3/ping` | 200 application/json | institution |

Every request above was made **unauthenticated**. None of these surfaces required a key to read.
