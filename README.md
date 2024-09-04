# API Testing Congress.gov Members

## Go to:
[Congress.gov API](https://api.congress.gov/)

Sign up for an API Key here: [Sign Up](https://api.congress.gov/sign-up/)

## Parameters for the `/member` API

### `format`, string
The data format. Value can be `xml` or `json`.

### `offset`, integer
The starting record returned. `0` is the first record.

### `limit`, integer
The number of records returned. The maximum limit is 250.

### `fromDateTime`, string
The starting timestamp to filter by update date. Use format: `YYYY-MM-DDT00:00:00Z`.

### `toDateTime`, string
The ending timestamp to filter by update date. Use format: `YYYY-MM-DDT00:00:00Z`.

### `currentMember`, string
The status of the member. Use `true` or `false`.

---

**Important:** The time format is Zulu time.  
*"Zulu time is generally used as a term for Universal Coordinated Time (UCT), sometimes called Universal Time Coordinated (UTC) or Coordinated Universal Time (but abbreviated UTC). Zulu time was created to eliminate the confusion caused by different time zones."*
