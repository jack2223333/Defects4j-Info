## JacksonXml

This projects contains [Jackson](https://github.com/FasterXML/jackson) extension component for reading and writing [XML](http://en.wikipedia.org/wiki/Xml) encoded data.

Further, the goal is to emulate how [JAXB](http://en.wikipedia.org/wiki/JAXB) data-binding works with "Code-first" approach (no support is added for "Schema-first" approach). Support for JAXB annotations is provided by [JAXB annotation module](https://github.com/FasterXML/jackson-modules-base/tree/master/jaxb); this module provides low-level abstractions (`JsonParser`, `JsonGenerator`, `JsonFactory`) as well as small number of higher level overrides needed to make data-binding work.

It is worth noting, however, that the goal is NOT to be full JAXB clone; or to be a general purpose XML toolkit.

Specifically:

- While XML serialization should ideally be similar to JAXB output, deviations are not automatically considered flaws (there are reasons for some differences)
- What should be guaranteed is that any XML written using this module must be readable using module as well ("read what I wrote"): that is, we do aim for full round-trip support
- From above: there are XML constructs that module will not be able to handle; including some cases JAXB (and other Java XML libraries) supports
- This module also support constructs and use cases JAXB does not handle: specifically, rich type and object id support of Jackson are supported.