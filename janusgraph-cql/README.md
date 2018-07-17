# Support for LDAP authentication on Cassandra

## License Issue

Such feature is supported by **DataStax Enterprise (DSE) Driver** , unfortunately its [license](https://www.google.com/url?q=https%3A%2F%2Fwww.datastax.com%2Fterms%2Fdatastax-dse-driver-license-terms&sa=D&sntz=1&usg=AFQjCNEbtD94UoPI4A-Ld-O_BOSAa59xzg) appears to be incompatible with **Apache 2.0** and hence, likely **ineligible to be included in JanusGraph by default** (see [dev forum topic](https://groups.google.com/forum/#!topic/janusgraph-dev/dCtm74lGgUg))

## Implementation

As suggested in [dev forum topic](https://groups.google.com/forum/#!topic/janusgraph-dev/dCtm74lGgUg) the implementation **use reflection to lookup for DSE Driver** so there isn't a **compile time dependency** and then a license violation
