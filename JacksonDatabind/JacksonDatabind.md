## **JacksonDatabind**

This project contains the general-purpose data-binding functionality and tree-model for [Jackson Data Processor](https://github.com/FasterXML/jackson). It builds on [Streaming API](https://github.com/FasterXML/jackson-core) (stream parser/generator) package, and uses [Jackson Annotations](https://github.com/FasterXML/jackson-annotations) for configuration. Project is licensed under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

While the original use case for Jackson was JSON data-binding, it can now be used to read content encoded in other data formats as well, as long as parser and generator implementations exist. Naming of classes uses word 'JSON' in many places even though there is no actual hard dependency to JSON format.