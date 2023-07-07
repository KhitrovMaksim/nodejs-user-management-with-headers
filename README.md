# nodejs-user-management.

## 4. REST.

### 4.2 User management: dates fields.

#### Task.

Continue your work with User Management REST Api.
1. Add  tech field to user profile records: created_at, updated_at, deleted_at. These fields should not be exposed at REST.
2. Add every user profile add header Last-Modified with value from updated_at.
3. Protect profile changes from update without knowledge about the last resource state by checking If-Unmodified-Since header.have pagination.
