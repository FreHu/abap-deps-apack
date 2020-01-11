# abap-deps-apack

Apack interface definitions

## Usage

If abaplint complains about a missing interface `zif_apack_manifest` or `if_apack_manifest`, update your `abaplint.json` with
```json
"dependencies": [
  {
      "url": "https://github.com/FreHu/abap-deps-apack",
      "folder": "/deps",
      "files": "/src/**/*.*"
  }
]
```