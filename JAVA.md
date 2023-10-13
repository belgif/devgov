# Java resources

## Tools and libraries

### Cryptography 
- [Bouncy Castle](https://www.bouncycastle.org/): lightweight cryptography API and generators/processors for OCSP, TSP, DANE, ...
- [Pac4j](https://www.pac4j.org): security framework for Spring/Spring Boot, Vert.x... supporting OAuth, OpenID Connect, SAML, JWT...
- [SSHJ](https://github.com/hierynomus/sshj): scp/sftp implementation with support for OpenPGP private keys

### Files

- [Aalto XML](https://github.com/FasterXML/aalto-xml): high performance Stax XML processor implementation (basic Stax API and Stax2 extension)
- [Apache PDF Box](https://pdfbox.apache.org/): low-level library for writing (and to some degree editing) PDF files, can also be used to add digital signatures to PDF
- [FastCSV](https://github.com/osiegmar/FastCSV): dependency-free RFC 4180 compliant CSV library for Java

### Geo

- [GeoTools](https://www.geotools.org/): various libraries for reading/writing geo files (SHP, geopackage...), coordinate conversions, geospatial operations (combining, diff/intersect)...
- [LocationTech Proj4j](https://github.com/locationtech/proj4j): library for converting coordinates between different geospatial coordinate reference systems, supports GSB correction grids

### Linked data

- [Eclipse RDF4J](https://rdf4j.org/): data store and library for reading and writing RDF (JSON-LD, Turtle, RDF/XML...), supporting SPARQL queries/updates and SHACL validation

### Misc

- [PicoCLI](https://picocli.info/): make it easier to create command line tools with validation framework for mandatory or optional parameters, help text... (alternative to Apache Commons CLI)

### Template engines

- [Freemarker](https://freemarker.apache.org/): template engine with built-in string functions, loops / sorts ...
- [Pebble](https://pebbletemplates.io/): slightly less powerful (but slightly faster and smaller) than Freemarker

### Testing

- [Greenmail](https://greenmail-mail-test.github.io/greenmail/): easy-to-use test suite of email (SMTP, POP3 and IMAP) servers for testing purposes, with JUnit 4/5 support
- [Testcontainers](https://testcontainers.com/): framework for providing throwaway Docker container with e.g. real databases, message brokers, web servers... (as opposed to just mocking these components)

### Web scraping

- [jsoup](https://jsoup.org): HTML parsing / webscraping library
