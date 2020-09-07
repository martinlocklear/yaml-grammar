YAML 1,2 Parsers
================

Generate YAML Parsers from the Spec

# Synopsis
```
make test
```

# Description

Here we generate 100% compliant YAML 1.2 parsers, in multiple programming languages, from the YAML 1.2 specification.

It works like this:

* Start with the grammar productions in the online [YAML 1.2 Spec](https://yaml.org/spec/1.2/spec.html#id2770814)
* Convert that into a [YAML 1.2 Spec as YAML](https://github.com/yaml/yaml-grammar/blob/master/yaml-spec-1.2.yaml)
* Convert this into a machine generated parser/grammar module in every programming language:
  * [CoffeeScript]()
  * [JavaScript]()
  * [Perl]()

# Next Steps

* Get the generated parser to pass 100% of the [YAML Test Suite](https://github.com/yaml/yaml-test-suite/)
* Generate equivalent grammar/parsers in several other languages
* Start refactoring the grammar to be simpler
  * While always passing the tests
* Create a new YAML 1.3 grammar
  * Start with 1.2 grammar
  * Apply RFCs as they become accepted
  * Generate and test all the language parsers
