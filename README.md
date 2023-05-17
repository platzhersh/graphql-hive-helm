# graphql-hive-helm

This is a self hosted version of GraphQL Hive. It is intended for development and testing purposes only.
It is not recommended to use this in production.

Based on: https://github.com/kamilkisiela/graphql-hive/blob/main/docker/docker-compose.community.yml

## Usage

### Dry run

```bash
helm upgrade --install registry ./hive --namespace hive --create-namespace --dry-run
```

### Install

```bash
helm upgrade --install registry ./hive --namespace hive --create-namespace
```