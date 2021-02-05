# Change Log

# 1.0.0

* Drop Python 2.7 support

# 0.1.1

- Add explicit support for Python 2 and 3

# 0.1.0

#### Additions
- Creation of Pack
- New Actions
  - Zones: `create`, `update`, `get`, `delete`, `search`, `list`
  - Records: `create`, `update`, `get`, `delete`
  - Data Sources: `create`, `update`, `get`, `delete`, `list`, `publish`
  - Data Feeds: `create`, `update`, `get`, `delete`, `list`
  - Monitors: `get`, `list`
  - Notify Lists: `get`, `list`
  - Stats: `qps`, `usage`
  - Account: `get`

#### Changes
- None

#### Fixes
- None

#### Known Issues

- `source.update` currently does not work. I beleive this is a bug with the SDK/API and have an issue opened in `ns1-python`
  - https://github.com/ns1/ns1-python/issues/17
- IPAM - All methods found in `ns1.rest.ipam.py` were excluded from scope of this initial release
- Monitor - `create`, `update`, and `delete` were excluded from scope of this initial release
- Notify Lists - `create`, `update`, and `delete` were excluded from scope of this initial release
