This is linter for CudaLint.
It adds support for JSON/YAML lexers using "jsonschema-lint".
https://github.com/jacksmith15/jsonschema-lint
That tool needs file "schema.json" near original file, like here:
https://github.com/jacksmith15/jsonschema-lint/tree/main/tests/assets/simple/numbers

Make sure that "jsonschema-lint" is installed on your system.
Run in terminal:
$ pip install jsonschema-lint
For YAML support:
$ pip install jsonschema-lint[yaml]

Ported from SublimeLinter-contrib-jsonschema-lint by Alexey Torgashin (CudaText).
License: MIT
