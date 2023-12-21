## Collections

The [Java Collections Framework](http://docs.oracle.com/javase/tutorial/collections/) was a major addition in JDK 1.2. It added many powerful data structures that accelerate development of most significant Java applications. Since that time it has become the recognised standard for collection handling in Java.

Commons-Collections seek to build upon the JDK classes by providing new interfaces, implementations and utilities. There are many features, including:

- Bag interface for collections that have a number of copies of each object
- BidiMap interface for maps that can be looked up from value to key as well and key to value
- MapIterator interface to provide simple and quick iteration over maps
- Transforming decorators that alter each object as it is added to the collection
- Composite collections that make multiple collections look like one
- Ordered maps and sets that retain the order elements are added in, including an LRU based map
- Reference map that allows keys and/or values to be garbage collected under close control
- Many comparator implementations
- Many iterator implementations
- Adapter classes from array and enumerations to collections
- Utilities to test or create typical set-theory properties of collections such as union, intersection, and closure