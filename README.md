# openapi-generator-php81-templates
openapi-generator template for PHP8.1(enum, type declarations)

## usage

### create package.json

```shell
npm init
```

### add this package(templates) as dependency

```shell
npm install "77web/openapi-generator-php81-templates#v1.0.1"
```

### run openapi-generator-cli with `-t` option

```shell
openapi-generator-cli generate -g php -i path/to/spec.yaml -c path/to/config.json -o ./ -t ./node_modules/quartetcom-openapi-generator-php81-templates/templates
```

## how it works

- Templating feature of openapi-generator https://openapi-generator.tech/docs/templating/
- based on official template https://github.com/OpenAPITools/openapi-generator/tree/master/modules/openapi-generator/src/main/resources/php
