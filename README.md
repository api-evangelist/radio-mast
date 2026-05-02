# Radio Mast (radio-mast)

The Radio Mast API allows you to integrate Radio Mast functionality into your app or website, including streaming network management, stream monitoring, listener analytics, and encoder credentials.

**APIs.yml URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/radio-mast/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Radio
- Streaming
- Analytics
- Audio
- Broadcasting

## Timestamps

- **Created:** 2025-02-12
- **Modified:** 2026-04-28

## APIs

### Radio Mast

REST API covering the Radio Mast streaming network and stream monitoring functionality, with analytics on listener sessions.

- **Documentation:** https://www.radiomast.io/docs/api/
- **Interactive Browser:** https://api.radiomast.io
- **Base URL:** `https://api.radiomast.io/v1`
- **OpenAPI:** [openapi/radio-mast-openapi.yml](openapi/radio-mast-openapi.yml)
- **Authentication:** API key via `Authorization` header

#### Resources

- **Radio Streams** — `radiostreams/radiomast/`, `radiostreams/external/`
- **Radio Stations** — `radiostations/`
- **Analytics** — listener-session time-series, aggregate, reports
- **Listener Pools** — `listener-pools/`

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
