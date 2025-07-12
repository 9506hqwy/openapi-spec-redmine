# OpenAPI Schema for Redmine Server Web API

## Generating

Bundle one file.

```sh
redocly bundle -d --remove-unused-components -o openapi.yml ./schema/openapi.yml
```

Verify OpenAPI schema format.

```sh
redocly lint openapi.yml
```

Preview documents.

```sh
redocly preview-docs openapi.yml
```

## References

- [Redmine API](https://www.redmine.org/projects/redmine/wiki/rest_api)
