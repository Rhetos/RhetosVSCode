# Rhetos DSL syntax highlighting

This package provides syntax highlighting for [Rhetos DSL](https://github.com/rhetos/rhetos/wiki) scripts.

## Features

The syntax highlighting is enabled for .rhe files.

In addition to highlighting Rhetos DSL keywords, this plugin follows the Rhetos convention for writing C# code snippets in the single quotes (`'`) and SQL in double quotes (`"`). These code snippets will be displayed with the C# or SQL syntax highlighting.

## Known Issues

The language keywords list is taken from the *CommonConcepts* DSL package. Any additional custom-developed concepts are not automatically highlighted.

## Release Notes

### 0.0.1

Initial development based on the Rhetos DSL plugin for SublimeText3,
<https://github.com/Hugibeer/RhetosDSLSyntax>.
The code snippets are not yet migrated.
