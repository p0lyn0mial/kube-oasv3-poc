# kube-oasv3-poc

## to validate the spec
- download OASv3 schema from https://github.com/OAI/OpenAPI-Specification/tree/master/schemas/v3.0

- find a schema validator - https://json-schema.org/implementations.html#validator-command%20line
  
  note: OASv3 uses `JSON Schema Specification Wright Draft 00` also know as `Draft 5` according to https://json-schema.org/specification-links.html, 
  the linked page contains validators that support `draft-06` or later.
- valide the schema, e.g. `ajv validate -s schema3.json -d spec3.json`


