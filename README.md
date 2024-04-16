# keycloak-setup

This action sets up a Keycloak instance.

## Inputs

### `keycloak_version`

**Required** The installed version. Default `"latest"`.

### `keycloak_http_port`

**Optional** HTTP Port. Default `"8080"`.

### `keycloak_admin_user`

**Optional** Admin username. Default `"admin"`.

### `keycloak_admin_pass`

**Optional** Admin password. Default `"admin"`.

## Example usage

```yaml
uses: DreamsOfImran/keycloak-setup@master
with:
  keycloak_version: 24.0.1
  keycloak_http_port: 8080
  keycloak_admin_user: admin_user
  keycloak_admin_password: admin_pass
  keycloak_db: mysql
  keycloak_db_url_host: localhost:3306
  keycloak_db_username: keycloak
```
