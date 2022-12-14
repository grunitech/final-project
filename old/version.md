# Versioning

## About Versioning

`MAJOR.MINOR.PATCH(-alpha)`

```json
{
  "packageA": "1.2.3",
  "packageB": "~1.2.3",
  "packageC": "^1.2.3"
}
```

* A -> Always get `1.2.3`
* B -> Get the latest of `1.2.x`
* C -> Get the latest of `1.x.y`

## Npm install / update

Will never set a new MAJOR version.
