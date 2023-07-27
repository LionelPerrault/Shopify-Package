# @shopify/shopify-app-session-storage-postgresql

## 1.1.7

### Patch Changes

- 32296d7: Update @shopify/shopify-api dependency to 7.5.0
- Updated dependencies [32296d7]
  - @shopify/shopify-app-session-storage@1.1.6

## 1.1.6

### Patch Changes

- 93e9126: Updating @shopify/shopify-api dependency
- Updated dependencies [93e9126]
  - @shopify/shopify-app-session-storage@1.1.5

## 1.1.5

### Patch Changes

- b3453ff: Bumping @shopify/shopify-api dependency to latest version
- Updated dependencies [b3453ff]
  - @shopify/shopify-app-session-storage@1.1.4

## 1.1.4

### Patch Changes

- 278a759: Bumps [pg](https://github.com/brianc/node-postgres/tree/HEAD/packages/pg) from 8.10.0 to 8.11.0. See pg's [changelog](https://github.com/brianc/node-postgres/blob/master/CHANGELOG.md) for more details.

## 1.1.3

### Patch Changes

- e1d4f4f: Add @shopify/shopify-api as a peerDependencies entry for each session-storage package, to avoid API library conflicts (e.g., scopesArray.map error). Should help avoid issues like #93
- 1d007e8: Bumps [@shopify/shopify-api](https://github.com/LionelPerrault/Shopify-Package/shopify-api-js) from 7.0.0 to 7.1.0. See `@shopify/shopify-api`'s [changelog](https://github.com/LionelPerrault/Shopify-Package/shopify-api-js/blob/main/CHANGELOG.md) for more details.
- d4f3891: Bump pg from 8.9.0 to 8.10.0. See [changelog](https://github.com/brianc/node-postgres/blob/master/CHANGELOG.md) for details.
- Updated dependencies [e1d4f4f]
- Updated dependencies [1d007e8]
  - @shopify/shopify-app-session-storage@1.1.3

## 1.1.2

### Patch Changes

- e4f3415: Bump @shopify/shopify-api from 6.2.0 to 7.0.0. See [changelog](https://github.com/LionelPerrault/Shopify-Package/shopify-api-js/blob/main/CHANGELOG.md) for details.
- 8615a8a: PostgreSQL session storage to use a connection pool instead of a single client connection. Fixes #156, #168
- 3969855: Use decodeURIComponent on password, user, database name fields prior to calling underlying MySQL connection. Fixes #163. Also applied to postgresql adapter.
- Updated dependencies [e4f3415]
  - @shopify/shopify-app-session-storage@1.1.2

## 1.1.1

### Patch Changes

- 97346b3: Fix #132: mysql migrator was unable to detect already applied migrations
- Updated dependencies [97346b3]
  - @shopify/shopify-app-session-storage@1.1.1

## 1.1.0

### Minor Changes

- becc305: Migrations capabilities that can handle persistence changes for all session storage implementations

### Patch Changes

- 8cadd09: Modify postgres to make table and column names case sensitive. Fixes Shopify/shopify-api-js#460
- 8f5749f: Increase size of 'scope' column to 1024 for session storage implementation for RDBMS
- eaa6b18: Update to support PostgreSQL v15 breaking changes
- b6501b0: Bump typescript to 4.9.5
- 348b5af: Bump @ypes/pg to 8.6.6
- Updated dependencies [b6501b0]
- Updated dependencies [becc305]
  - @shopify/shopify-app-session-storage@1.1.0

## 1.0.2

### Patch Changes

- 222b755: Updating @shopify/shopify-api to v6.1.0
- Updated dependencies [222b755]
  - @shopify/shopify-app-session-storage@1.0.2

## 1.0.1

### Patch Changes

- 1eccbd6: Reapply a fix for a bug where the PostgreSQL session storage always attempted to create the sessions table
- 866b50c: Update dependencies on shopify-api v6.0.2
- Updated dependencies [866b50c]
  - @shopify/shopify-app-session-storage@1.0.1

## 1.0.0

### Major Changes

- Initial public release of @shopify/shopify-app-session-storage-postgresql
