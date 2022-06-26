## Migration Guide
The gherking@2 introduced structural changes in GherKing. The previously built-in precompliers were moved to separate repositories to offer a modular solution.

In order to successfully migrate to gherking@2 from the previous version (gherkin-precompiler, gherkin-assembler, gherking@0.0.3) the following steps are required:
* In the precompiler.json switch "type" keys to "path" in case of built-in precompilers, and update their values to the new name of the precompiler.



gherking@0.0.3
```shell
// precompiler.json

"type": "ForLoop"
```

gherking@2
```shell
// precompiler.json

"path": "gpc-for-loop"
```

* Include each precomplier you wish to use as a dependency in the package.json file.
